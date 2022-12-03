<template>
  <firstComponent></firstComponent>
</template>

<script>
import firstComponent from './components/firstComponent.vue'

export default {
  name: 'App',
  components: {
    firstComponent
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
  background: linear-gradient(to bottom right, #f279e6, #7b79f2) no-repeat;
  height: 100%;
  margin: 0px;
}
</style>
