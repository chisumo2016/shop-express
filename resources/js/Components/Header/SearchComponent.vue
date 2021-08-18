<template>
    <div class="flex flex-col">
        <div class="flex w-full">
            <input class="w-120 focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-transparent rounded-l-md border-2 focus:border-red-500 border-r-0"
                type="text" placeholder="rugby new Zealand">
            <select class="w-1/4 focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-transparent border-2 border-red-500 border-r-0 border-l-0">
                <option value="0">All Categories</option>
                <option value="2">Food</option>
                <option value="6">Home Appliances</option>
                <option value="7">Computer &amp; Office</option>
                <option value="13">Home Improvement</option>
                <option value="15">Home &amp; Garden</option>
                <option value="18">Sports &amp; Entertainment</option>
                <option value="21">Education &amp; Office Supplies</option>
                <option value="26">Toys &amp; Hobbies</option>
                <option value="30">Security &amp; Protection</option>
                <option value="34">Automobiles &amp; Motorcycles</option>
                <option value="39">Lights &amp; Lighting</option>
                <option value="44">Consumer Electronics</option>
                <option value="66">Beauty &amp; Health</option>
                <option value="322">Shoes</option>
                <option value="502">Electronic Components &amp; Supplies</option>
                <option value="509">Cellphones &amp; Telecommunications</option>
                <option value="1420">Tools</option>
                <option value="1501">Mother &amp; Kids</option>
                <option value="1503">Furniture</option>
                <option value="1509">Jewelry &amp; Accessories</option>
                <option value="1511">Watches</option>
                <option value="1524">Luggage &amp; Bags</option>
                <option value="200002489">Hair Extensions &amp; Wigs</option>
                <option value="205965401">Virtual Goods</option>
                <option value="200000875">Novelty &amp; Special Use</option>
                <option value="100003235">Weddings &amp; Events</option>
                <option value="100003109">Women's Clothing</option>
                <option value="100003070">Men's Clothing</option>
                <option value="205776616">Apparel Accessories</option>
                <option value="205779615">Underwear &amp; Sleepwears</option>
                <option value="0">In All Categories</option>
            </select>
            <button class="bg-red-500 text-white px-2 rounded-r-md">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                </svg>
            </button>
            <Cart />
        </div>
        <div class="w-10/12 text-xs text-gray-400 grid grid-cols-6 divide-2 divide-x divide-gray-300  space-x-2 py-2">
            <a href="/" class="hover:text-red-500 text-center">bosch laser </a>
            <a href="/" class="hover:text-red-500 text-center">men vulcanize shoes</a>
            <a href="/" class="hover:text-red-500 text-center">sock boots women</a>
            <a href="/" class="hover:text-gray-50 text-center">funny underwear</a>
            <a href="/" class="hover:text-red-500 text-center">sudader</a>

        </div>
    </div>
</template>

<script>

import Cart from './CartComponent'

export default {
    components:{
        Cart
    }
}
    // import { defineComponent} from '@vue/compositions-api'
    //  export  default  defineComponent({
    //      setup(){
    //
    //      },
    //  })

</script>
