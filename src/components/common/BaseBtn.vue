<template>
  <div>
    <button>{{ props.nameBtn }}</button>
  </div>
</template>

<script setup>
import { defineProps } from "vue";
// const emit

const props = defineProps({
  nameBtn:{
    type: String,
  }
});
</script>

<style scoped></style>
