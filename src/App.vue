<template>
  <div>
    <h2>Your Shopping Cart</h2>

    <!-- If items array is not empty show this -->
    <ul v-if="items.length > 0">
      <!-- add loop to show all items -->
      <!-- give :key attribute the value of current index -->
      <li :key=""></li>

      <!-- output should follow this pattern -->
      <!-- name - price x quantity -->
    </ul>

    <!-- else show this -->
    <p>Your cart is empty</p>
  </div>
</template>

<script setup>
import { toRefs } from "vue";

// ignore code below
const props = defineProps({
  items: {
    type: Array,
    required: false,
    default: [
      {
        name: "Product A",
        price: 9.99,
        quantity: 2,
      },
      {
        name: "Product B",
        price: 14.99,
        quantity: 1,
      },
      {
        name: "Product C",
        price: 19.99,
        quantity: 3,
      },
    ],
  },
});
// ignore code above

const { items } = toRefs(props);
</script>
