<template>
<div class="bg-head" >
  <Navbar/>
  <Hero/>
  <Model/>
  <Pricing class="mt-5"/>
  <Tutorial/>
 
 </div>
</template>

<style scoped>
.bg-head{
  background-color: #f9eccd;
}
</style>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },
  name: 'In dexPage'
  
  
}





</script>
