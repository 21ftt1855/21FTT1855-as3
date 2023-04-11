<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" /> -->
  <div class="p-10 m-5 bg-gradient-to-r from-blue-100 to-violet-300 md:flex md:item-center md:justify-items">
    <img src="/public/student.jpg" alt="Student Image" class="md:w-1/4 rounded-3xl border border-4 border-solid border-teal-500">
    <table class="border border-solid border-black m-5 p-5">
      <tr class=" border border-solid border-black text-center">
        <td colspan="2">Student's Information</td>
      </tr>
      <tr class="border border-solid border-black">
        <td class="p-2 border border-solid border-black">Name: </td>
        <td class="p-2 border border-solid border-black">Nur Aimuni Nadhirah</td>
      </tr>
      <tr class="border border-solid border-black">
        <td class="p-2 border border-solid border-black">Student ID: </td>
        <td class="p-2 border border-solid border-black">21FTT1855</td>
      </tr>
      <tr class="border border-solid border-black">
        <td class="p-2 border border-solid border-black">Course: </td>
        <td class="p-2 border border-solid border-black">Level 5 Diploma in Web Development</td>
      </tr>
      <tr class="border border-solid border-black">
        <td colspan="2" class="p-2 border border-solid border-black">I am a student taking Web Development in Politeknik Brunei!</td>
      </tr>
    </table>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
