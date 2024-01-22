<script>

import AppHeader from './components/AppHeader.vue';

export default {
  data() {
    return {
    }
  },
  methods: {
    incrementCount() {
      this.count++
    }
  },
  components: {
    AppHeader
  },
}
</script>

<template>
  <AppHeader />
  <div>
      <button @click="incrementCount()">
      Incrementa</button>
  </div>
</template>

<style scoped>

</style>
