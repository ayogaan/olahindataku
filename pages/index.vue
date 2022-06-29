<template>
<div class="bg-head" >
  <Navbar/>
  <Hero/>
  <div class="p-4" id="model">
  <Model class="mx-4" />
  </div>
  <Pricing class="mt-5"/>
  <Tutorial/>
 
 </div>
</template>

<style scoped>
.bg-head{
  background-color: #f9eccd;
}


</style>
<style>
html {
  scroll-behavior: smooth;
}
</style>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },
  name: 'In dexPage'
  
  
}





</script>
