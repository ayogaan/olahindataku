<template>
  <!-- component -->
<nav class="bg-white backdrop-blur-md shadow-lg fixed w-full z-10">
			<div class="max-w-8xl mx-auto lg:px-8 px-4 ">
				<div class="flex justify-between">
					<div class="flex space-x-7">
						<div>
							<!-- Website Logo -->
							<a href="#" class="flex items-center py-4 px-2">
								<span class="lg:text-2xl font-extrabold tracking-wide uppercase">
        						Olah Dataku
      							</span>
							</a>
						</div>
						<!-- Primary Navbar items 
						<div class="hidden md:flex items-center space-x-1 hidden">
							<a href="" class="py-4 px-2 text-green-500 border-b-4 border-green-500 font-semibold ">Home</a>
							<a href="" class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300">Services</a>
							<a href="" class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300">About</a>
							<a href="" class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300">Contact Us</a>
						</div>
						-->
					</div>
					<!-- Secondary Navbar items -->
					
					<!-- Mobile menu button 
					<div class="md:hidden flex items-center ">
						<button @click="testFunction" class="outline-none mobile-menu-button">
						<svg class=" w-6 h-6 text-gray-500 hover:text-green-500 "
							x-show="!showMenu"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path d="M4 6h16M4 12h16M4 18h16"></path>
						</svg>
					</button>
					</div>
					-->
				</div>
			</div>
			<!-- mobile menu 
			<div class="hidden mobile-menu transition duration-300 ease-in-out">
				<ul class="">
					<li class="active"><a href="index.html" class="block text-sm px-2 py-4 text-white bg-green-500 font-semibold">Home</a></li>
					<li><a href="#services" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Services</a></li>
					<li><a href="#about" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">About</a></li>
					<li><a href="#contact" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Contact Us</a></li>
				</ul>
			</div>
		-->
		</nav>
</template>




<script>
export default {
  name: 'Navbar',
  methods:{
    testFunction: function(event) {
     
      document.querySelector(".mobile-menu").classList.toggle("hidden");
    }
  }
}

</script>

