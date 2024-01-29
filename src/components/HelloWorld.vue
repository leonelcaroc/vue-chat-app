<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div>This is vue chat application</div>
</template>

<style scoped></style>
