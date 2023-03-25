<template>
  <!-- Add event listener using 
    templating syntax for Vue.js 
    and update ref's value -->
  <button id="h1-btn">Awesome h1</button>
  <button id="p-btn">Awesome p</button>

  <!-- Make content of this h1 dynamic -->
  <h1 id="h1"></h1>

  <!-- Make content of this p dynamic -->
  <p id="p"></p>

  <!-- NOTE: don't add any other html element in template -->
</template>

<script setup>
import { ref } from "vue";

// Hint: Create 2 reactive variable using `ref` function
// and add it to template.
</script>
