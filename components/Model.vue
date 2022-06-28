<template>
<!-- component -->
<div class="py-16 bg-white overflow-hidden container mx-auto rounded-md  shadow-lg">
    <div class="container m-auto px-6 space-y-8 text-gray-500 md:px-12">
        <div>
            <span class="text-gray-600 text-lg font-semibold">Plugin yang kami miliki</span>
        </div>
        <div class="mt-16 grid border divide-x divide-y rounded-xl overflow-hidden sm:grid-cols-2 lg:divide-y-0 lg:grid-cols-3 xl:grid-cols-4">
  
            <div v-for="d in dat" :key="d.nama" class="relative group bg-white transition hover:z-[1] hover:shadow-2xl">
                <div class="relative p-8 space-y-8">
                    <img src="https://tailus.io/sources/blocks/stacked/preview/images/avatars/burger.png" class="w-10" width="512" height="512" alt="burger illustration">
                    
                    <div class="space-y-2">
                        <h5 class="text-xl text-gray-800 font-medium transition group-hover:text-yellow-600">{{d.nama}}</h5>
                        <p class="text-sm text-gray-600">{{d.deskripsi}}</p>
                    </div>
                    <a href="#" class="flex justify-between items-center group-hover:text-yellow-600">
                        <span class="text-sm">Read more</span>
                        <span class="-translate-x-4 opacity-0 text-2xl transition duration-300 group-hover:opacity-100 group-hover:translate-x-0">&RightArrow;</span>
                    </a>
                </div>
            </div>


                    </div>
       
    </div>

</div> 
</template>




<script>
import axios from 'axios'
import qs from "qs"
export default {
  name: 'Model',
  data(){
      return{
          dat: []
      }
  } ,
  methods:{
    asu(){
        axios.get(
            'http://localhost:5001/mongoaccess'
        ).then(res=>{
            this.dat = res.data
        
        })
    }
  },
  created :function(){
      this.asu()
  }
  

}
</script>

