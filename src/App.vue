<template>
  <Enfant class="container" @click="handler" />
</template>

<script setup lang="ts">
import Enfant from './Enfant.vue';

function handler() {
  console.log('clic !');
}
</script>

<style scoped lang="scss">
.container {
  color: blue;
}
</style>
