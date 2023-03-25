<template>
  <button @click="inc" id="inc">+</button>
  <button @click="dec" id="dec">-</button>

  <!-- Add count below -->
  <p id="ref">{{}}</p>

  <!-- Add computed property below -->
  <p id="computed">{{}}</p>
</template>

<script setup>
import { defineProps } from "vue";

const props = defineProps({
  books: {
    type: Array,
    required: false,
    default: [],
  },
});

// HINT: Use 'ref' function of vue

function inc() {
  // increment your ref here
}
function dec() {
  // decrement your ref here
}

// property to use in computed : props.books
</script>
