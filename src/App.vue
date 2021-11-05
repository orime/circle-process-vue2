<template>
  <div id="app">
    <CircleProgress :value="60" :size="150" :color="'#d36'"  :duration="3000" />
  </div>
</template>

<script>
import CircleProgress from './components/CircleProgress.vue'

export default {
  name: 'App',
  components: {
    CircleProgress
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
