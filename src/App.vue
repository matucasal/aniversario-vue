<template>
  
  <div id="app">
    <SliderAniversario/>
  </div>
</template>

<script>
import SliderAniversario from './components/SliderAniversario.vue'

export default {
  name: 'app',
  components: {
    SliderAniversario
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
