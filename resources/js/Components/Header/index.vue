<template>
    <TopNavbar />
    <div class="flex items-center container mx-auto md:px-64 bg-white py-3">
        <Logo/>
        <Search/>
    </div>
    <!--        <Cart/>-->
</template>

<script>
import TopNavbar from './TopNavbar'
import  Logo    from    './LogoHeader'
import  Search  from    './SearchComponent'
// import  Cart    from    './CartComponent'

export default {
    //declare inside component
   components: {
       TopNavbar,
       Logo,
       Search,
       // Cart
   }
}
</script>

<style scoped>

</style>
