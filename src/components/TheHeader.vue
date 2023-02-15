<script setup></script>
<template>
   <header class="flex itmes-center justify-between p-3 shadow-lg">
      <img class="w-20" src="../assets/LOGO.png"/>
      <div class="space-x-2 m-2">
        <RouterLink to="/login">
      <button class="bg-[#1385D2] p-2 rounded-md text-white my-4">GITHUB</button>
        </RouterLink>
        <RouterLink to="/signup">
      <button class="bg-[#1385D2] text-white p-2 rounded-md">CONTACT ME</button>
        </RouterLink>
      </div>
  </header>
</template>