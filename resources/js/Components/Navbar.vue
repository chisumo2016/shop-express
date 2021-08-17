<template>
    <header class="bg-gray-100">
        <nav class="container mx-auto px-8">
            <ul class="flex justify-end space-x-8 py-3 text-sm">
                <li>
                    <a href="/">Sell on shop Express</a>
                </li>
                <li>
                    <a href="/">Help</a>
                </li>
                <li>
                    <a href="/" class="flex text-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                        </svg>
                        Wishlist
                    </a>
                </li>
                <li class="relative cursor-pointer" @mouseover="isAccountLinkHovered  = true">
                 <span :class="isAccountLinkHovered ? 'text-red-400': '' " class="flex items-center">
                       <svg xmlns="http://www.w3.org/2000/svg" class="h-65 w-5  mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z" />
                        </svg>
                     Account</span>
                    <div class="absolute right-0 p-4 w-max h-max bg-gray-100 mt-3" v-if="isAccountLinkHovered"  @mouseleave="isAccountLinkHovered =false">
                        <div class="flex space-x-2 py-2 border-b-1 border-gray-200">
                            <button class="bg-red-500 text-white py-2 px-8 text-center font-bold rounded-sm">Join</button>
                            <button class="bg-red-100 text-red-500 py-2 text-center font-bold rounded-sm">Sign in</button>
                        </div>
                        <ul class="my-3 text-sm">
                            <li>
                                <a href="">My Orders</a>
                            </li>
                            <li>
                                <a href="">My Wishlist</a>
                            </li>
                            <li>
                                <a href="">My Coupon</a>
                            </li>
                            <li>
                                <a href="">Message center</a>
                            </li>
                        </ul>
                    </div>
                </li>


            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    data(){
        return{
            isAccountLinkHovered: false,
        }
    }
}
</script>

<style scoped>

</style>
