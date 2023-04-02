<template>
  <div v-if="post">
    <p>{{ post.title }}</p>
  </div>
</template>

<script setup>
import { ref } from "vue";

const post = ref(null);

const postId = ref(5);

// USE THIS URL
// https://jsonplaceholder.typicode.com/posts/1 <- replace 1 with actual post id ref value
</script>
