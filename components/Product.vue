<template>
<!-- component -->
<section>
  <div class="relative max-w-screen-xl px-4 py-8 mx-auto">
    <div class="py-8">
      <h1 class="text-2xl mt-8 font-bold lg:text-3xl">
        Regression Model
      </h1>
      <span class="inline-block mt-1 w-12 h-1 bg-green-700"></span>

     
    </div>

    <div class="grid gap-8 lg:items-start lg:grid-cols-4">
      <div class="lg:col-span-3">
        <div class="relative mt-4">
          <img
            alt=""
            src=""
            class="w-full rounded-xl h-72 lg:h-[540px] object-cover"
          />

          <div class="absolute bottom-4 left-1/2 -translate-x-1/2 rounded-full bg-black/75 text-white px-3 py-1.5 inline-flex items-center">
            <svg
              class="w-4 h-4"
              xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"
            >
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0zM10 7v3m0 0v3m0-3h3m-3 0H7" />
            </svg>

            <span class="text-xs ml-1.5">
              Hover to zoom
            </span>
          </div>
        </div>

      </div>

      <div class="lg:top-8 lg:sticky">
        <form class="space-y-4 lg:pt-8">
          <fieldset >
            <legend class="text-lg mt-5 font-bold">
              Accuracy
            </legend>

            <div class="flex mt-2 space-x-1">
             <legend class="text-lg">
              83%
            </legend>
            </div>
          </fieldset>

          

          
          <div>
            <p class="text-xl font-bold">
              $19.99
            </p>
          </div>

          <button
            type="submit"
            class="w-full px-6 py-3 text-sm font-bold tracking-wide text-white uppercase bg-red-700 rounded"
          >
            Get Token
          </button>

          <button
            type="button"
            class="w-full px-6 py-3 text-sm font-bold tracking-wide uppercase bg-gray-100 border border-gray-300 rounded"
          >
            I Have Token
          </button>
        </form>
      </div>

      <div class="lg:col-span-3">
        <div class="prose max-w-none">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem ad labore nostrum, a explicabo iste est dolorem deserunt id ullam magni accusamus saepe, nulla sed sint reiciendis, aperiam cumque officiis!</p>

          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi eveniet ipsam mollitia nesciunt illo! Suscipit, corrupti!</p>

          <h3>Features</h3>

          <ul>
            <li>Smooth neck design</li>
            <li>Breathable fabric</li>
            <li>Odour prevention</li>
            <li>Made from recycled materials</li>
          </ul>
      </div>
      </div>
    </div>
  </div>
</section>

</template>

<style>
  .prose h3 {
    margin-bottom: 1rem;
    padding-bottom: 0.5rem;
    border-bottom: 1px solid rgb(243 244 246);

    /* @apply mb-1 pb-2 border-b border-gray-200; */
  }

  .prose iframe {
    width: 100%;
    margin-top: 1.5rem;
    aspect-ratio: 16 / 9;
    border-radius: 0.75rem;

    /* @apply w-full aspect-video mt-6 rounded-xl; */
  }
</style>


<script>

export default {
  name: 'Product',
  data(){
      return{
          dat: []
      }
  } ,
 
  created :function(){
      
  }
  

}
</script>

