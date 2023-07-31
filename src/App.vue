<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    <Car></Car>
    <Car></Car>
    <Car></Car>
  </div>
</template>

<script>
import Car from './components/Car.vue'

export default {
  name: 'App',
  components: {Car},
  data() {
    return {
      msg : '汽车信息'
    }
  }
}
</script>

<style>

</style>
