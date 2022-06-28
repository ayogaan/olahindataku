<template>
<!-- component -->
<section>
  <div class="max-w-screen-xl px-4 py-8  mx-auto">
    <div class="py-8" >

      <h2 class="mt-8 my-5 text-2xl font-extrabold tracking-wide uppercase lg:text-3xl">
        Models
      </h2>
      <span class="inline-block mt-1 w-12 h-1 bg-green-700"></span>

    </div>

    <div class="grid grid-cols-2 mt-8 lg:grid-cols-4 gap-x-4 gap-y-8">
      <a href="" class="block">
        <div class="flex justify-center">
          <strong class="relative h-6 px-4 text-xs leading-6 text-white uppercase bg-black"> New </strong>
        </div>

        <img
          alt="Trainer Product"
          src="https://images.unsplash.com/photo-1491553895911-0055eca6402d"
          class="object-cover w-full -mt-3 h-96"
        />

        <h5 class="mt-4 text-sm text-black/90">
          Limited Edition Sports Trainer
        </h5>

        <div class="flex items-center justify-between mt-4 font-bold">
          <p class="text-lg">
            $189.99
          </p>

          <p class="text-xs tracking-wide uppercase">
            6 Colors
          </p>
        </div>
      </a>

      <a href="" class="block">
        <div class="flex justify-center">
          <strong class="relative h-6 px-4 text-xs leading-6 text-white uppercase bg-black"> New </strong>
        </div>

        <img
          alt="Trainer Product"
          src="https://images.unsplash.com/photo-1491553895911-0055eca6402d"
          class="object-cover w-full -mt-3 h-96"
        />

        <h5 class="mt-4 text-sm text-black/90">
          Limited Edition Sports Trainer
        </h5>

        <div class="flex items-center justify-between mt-4 font-bold">
          <p class="text-lg">
            $189.99
          </p>

          <p class="text-xs tracking-wide uppercase">
            6 Colors
          </p>
        </div>
      </a>

      <a href="" class="block">
        <div class="flex justify-center">
          <strong class="relative h-6 px-4 text-xs leading-6 text-white uppercase bg-black"> New </strong>
        </div>

        <img
          alt="Trainer Product"
          src="https://images.unsplash.com/photo-1491553895911-0055eca6402d"
          class="object-cover w-full -mt-3 h-96"
        />

        <h5 class="mt-4 text-sm text-black/90">
          Limited Edition Sports Trainer
        </h5>

        <div class="flex items-center justify-between mt-4 font-bold">
          <p class="text-lg">
            $189.99
          </p>

          <p class="text-xs tracking-wide uppercase">
            6 Colors
          </p>
        </div>
      </a>

      <a href="" class="block">
        <div class="flex justify-center">
          <strong class="relative h-6 px-4 text-xs leading-6 text-white uppercase bg-black"> New </strong>
        </div>

        <img
          alt="Trainer Product"
          src="https://images.unsplash.com/photo-1491553895911-0055eca6402d"
          class="object-cover w-full -mt-3 h-96"
        />

        <h5 class="mt-4 text-sm text-black/90">
          Limited Edition Sports Trainer
        </h5>

        <div class="flex items-center justify-between mt-4 font-bold">
          <p class="text-lg">
            $189.99
          </p>

          <p class="text-xs tracking-wide uppercase">
            6 Colors
          </p>
        </div>
      </a>

       <a href="" class="block">
        <div class="flex justify-center">
          <strong class="relative h-6 px-4 text-xs leading-6 text-white uppercase bg-black"> New </strong>
        </div>

        <img
          alt="Trainer Product"
          src="https://images.unsplash.com/photo-1491553895911-0055eca6402d"
          class="object-cover w-full -mt-3 h-96"
        />

        <h5 class="mt-4 text-sm text-black/90">
          Limited Edition Sports Trainer
        </h5>

        <div class="flex items-center justify-between mt-4 font-bold">
          <p class="text-lg">
            $189.99
          </p>

          <p class="text-xs tracking-wide uppercase">
            6 Colors
          </p>
        </div>
      </a>
    </div>
  </div>

  <ol class="flex my-5 justify-center space-x-1 text-xs font-medium">
  <li>
    <a href="/?page=1" class="inline-flex items-center justify-center w-8 h-8 border border-gray-100 rounded">
      <svg xmlns="http://www.w3.org/2000/svg" class="w-3 h-3" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z" clip-rule="evenodd" />
      </svg>
    </a>
  </li>

  <li>
    <a href="/?page=1" class="block w-8 h-8 leading-8 text-center border border-gray-100 rounded"> 1 </a>
  </li>

  <li class="block w-8 h-8 leading-8 text-center text-white bg-blue-600 border-blue-600 rounded">2</li>

  <li>
    <a href="/?page=3" class="block w-8 h-8 leading-8 text-center border border-gray-100 rounded"> 3 </a>
  </li>

  <li>
    <a href="/?page=4" class="block w-8 h-8 leading-8 text-center border border-gray-100 rounded"> 4 </a>
  </li>

  <li>
    <a href="/?page=3" class="inline-flex items-center justify-center w-8 h-8 border border-gray-100 rounded">
      <svg xmlns="http://www.w3.org/2000/svg" class="w-3 h-3" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd" />
      </svg>
    </a>
  </li>
</ol>

</section>
</template>




<script>

export default {
  name: 'Products',
  data(){
      return{
          dat: []
      }
  } ,
 
  created :function(){
      
  }
  

}
</script>

