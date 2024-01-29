<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="font-bold underline text-red-600">Hello world!</div>
</template>

<style></style>
