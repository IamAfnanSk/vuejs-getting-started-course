<template>
  <button @click="inc">+</button>
  <button @click="dec">-</button>

  <!-- Add count below -->
  <p id="ref">{{}}</p>

  <!-- Add computed property below -->
  <p id="computed">{{}}</p>
</template>

<script setup>
// HINT: Use 'ref' function of vue

function inc() {
  // increment your ref here
}
function dec() {
  // decrement your ref here
}

// property to use in computed : props.books
</script>
