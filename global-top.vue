<template>
  <input type="number" v-model="width" style="top: 0px;">
  <Watermark :width="width" />
</template>

<script setup lang="ts">
import { ref } from "vue";

const width = ref(180);
</script>
