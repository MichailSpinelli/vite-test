<script>
import AppHeader from './components/AppHeader.vue';
export default {
  data() {
    return { count: 0 }
  },
  components: {
    AppHeader
  }
};
</script>

<template>
  <AppHeader></AppHeader>
  <h1>
    ciao
  </h1>
  <p>
    {{ count }}
  </p>

  <button @click="count++">
    incrementa count
  </button>
</template>

<style scoped>
</style>

