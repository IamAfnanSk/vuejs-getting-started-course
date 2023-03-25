<template>
  <button @click="inc" id="inc">+</button>
  <button @click="dec" id="dec">-</button>

  <!-- Add count below -->
  <p id="ref">{{}}</p>

  <!-- Add computed property below -->
  <p id="computed">{{}}</p>
</template>

<script setup>
import { toRef } from "vue";

// Ignore code below
const props = defineProps({
  books: {
    type: Array,
    required: false,
    default: [],
  },
});

const { books } = toRef(props);
// Ignore code above

// HINT: Use 'ref' function of vue to create a ref for count

function inc() {
  // increment your ref here
}
function dec() {
  // decrement your ref here
}

// name of ref to use in computed:- books
</script>
