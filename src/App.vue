<template>
  <div v-if="post">
    <p>{{ post.title }}</p>
  </div>
</template>

<script setup>
import { ref, toRefs } from "vue";
import fetch from "cross-fetch";

const props = defineProps({
  postId: {
    type: Number,
    required: false,
    // DONT CHANGE DEFAULT VALUE
    default: 5,
  },
});

const { postId } = toRefs(props);

const post = ref(null);

// USE THIS URL
// https://jsonplaceholder.typicode.com/posts/1 <- replace 1 with actual post id ref value
</script>
