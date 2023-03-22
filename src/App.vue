<script setup>

import HelloWorld from './components/HelloWorld.vue'
import AppTitle from './components/AppTitle.vue';

export default {
  components: {
    AppTitle,
    HelloWorld
  }
}
</script>

<template>
  <AppTitle></AppTitle>
  <HelloWorld></HelloWorld>
</template>

<style scoped></style>
