<template>
  <div>
    <Caculator />
  </div>
</template>

<script>
import Caculator from './components/Caculator.vue'

export default {
  name: 'App',
  components: {
    Caculator
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
