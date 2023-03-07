<script setup></script>
<template>

  <div class="flex justify-center items-center w-screen h-screen bg-white">
	
	<div class="container mx-auto my-4 px-4 lg:px-20">

		<div class="w-full p-8 my-4 md:px-12 lg:w-9/12 lg:pl-20 lg:pr-40 mr-auto rounded-2xl shadow-2xl">
			<div class="flex">
				<h1 class="font-semibold uppercase text-xl text-blue-400">Send me a <br /> message</h1>
			</div>
			<div class="grid grid-cols-1 gap-5 md:grid-cols-2 mt-5">
				<input class="w-full bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline"
            type="text" placeholder="First Name*" />
				<input class="w-full bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline"
            type="text" placeholder="Last Name*" />
				<input class="w-full bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline"
            type="email" placeholder="Email*" />
				<input class="w-full bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline"
            type="number" placeholder="Phone*" />
        </div>
				<div class="my-4">
					<textarea placeholder="Message*" class="w-full h-32 bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline"></textarea>
				</div>
				<div class="my-2 w-1/2 lg:w-1/4">
					<button class="uppercase text-sm font-bold tracking-wide bg-blue-400 text-gray-100 p-3 rounded-lg w-full focus:outline-none focus:shadow-outline">
            Send Message
          </button>
				</div>
			</div>

			<div
				class="w-full lg:-mt-96 lg:w-2/6 px-8 py-12 ml-auto bg-blue-400 rounded-2xl">
				<div class="flex flex-col text-white">
					<h1 class="font-semibold uppercase text-xl my-4">my contacts</h1>
					<h2 class="text-lg underline"> Email
					</h2>
           <p class="text-white">paulnyamawi18@gmail.com</p>
		
          
          <div class="flex my-4 w-2/3 lg:w-1/2">
            <div class="flex flex-col">
              <i class="fas fa-phone-alt pt-2 pr-2" />
            </div>
            <div class="flex flex-col">
              <h1 class="font-semibold uppercase text-xl my-4">call me</h1>
              <p class="text-white">Tel: +245792857288</p>
              <p class="text-white">Fax: +254759732432</p>
            </div>
          </div>
          
        </div>
      </div>
    </div>
   
</div>

</template>