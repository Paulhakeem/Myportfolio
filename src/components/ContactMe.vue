<script setup>
  import { ref } from 'vue'
  import emailjs from '@emailjs/browser'


  const sendEmail = () => {
    emailjs.sendForm('service_0br48ej', 'template_d8y6l1s', value.$refs.form, 'yz6D6HZgDaZq2vG80')
        .then((result) => {
            alert('SUCCESS!', result.text);
        }, (error) => {
            alert('FAILED...', error.text);
        });
  }
  
</script>
<template>
 
  <form action="https://formspree.io/f/xvonqvwp" method="POST">
  <div class="flex justify-center items-center w-screen h-screen bg-white">
	
	<div class="container mx-auto my-4 px-4 lg:px-20 md:my-96">

		<div class="w-full p-8 my-4 md:px-12 lg:w-9/12 lg:pl-20 lg:pr-40 mr-auto rounded-2xl shadow-2xl">
			<div class="flex">
				<h1 class="font-semibold uppercase text-xl text-blue-400">Send me a <br /> message</h1>
			</div>
			<div class="grid grid-cols-1 gap-5 md:grid-cols-2 mt-5">
				<input type="text" class="w-full bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline"
             placeholder="First Name*" required="required"/>
				<input type="text" class="w-full bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline"
             placeholder="Last Name*" required="required"/>
				<input class="w-full bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline"
            type="email" placeholder="Email*" required="required"/>
				<input type="number" class="w-full bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline"
             placeholder="Phone*" required="required"/>
        </div>
				<div class="my-4">
					<textarea type="message" placeholder="Message*" class="w-full h-32 bg-gray-100 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline" required="required"></textarea>
				</div>
				<div class="my-2 w-1/2 lg:w-1/4">
					<button type="submit" class="uppercase text-sm font-bold tracking-wide bg-blue-400 text-gray-100 p-3 rounded-lg w-full focus:outline-none focus:shadow-outline">
            Send Message
          </button>
				</div>
			</div>
  
			<div
				class="w-full lg:-mt-96 lg:w-2/6 px-8 py-12 ml-auto bg-blue-400 rounded-2xl">
				<div class="flex flex-col text-white">
					<h1 class="font-semibold uppercase text-xl my-4 pl-2">my contacts</h1>
					<h2 class="text-lg underline pl-2"> Email
					</h2>
           <p class="text-white pl-2 hover:underline cursor-pointer">paulnyamawi18@gmail.com</p>
		
          
          <div class="flex my-4 w-2/3 lg:w-1/2">
            <div class="flex flex-col">
              <i class="fas fa-phone-alt pt-2 pr-2" />
            </div>
            <div class="flex flex-col">
              <h2 class="text-lg underline"> Phone Numbers
					</h2>
              <p class="text-white">Tel1: +245792857288</p>
              <p class="text-white">Tel2: +254759732432</p>
            </div>
          </div>
          
        </div>
      </div>
    </div>
   
</div>
   </form>
</template>