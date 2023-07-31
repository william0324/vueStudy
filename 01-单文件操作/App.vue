<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <ComponentTwo></ComponentTwo>
    <ComponentThree></ComponentThree>
  </div>
</template>

<script>
import ComponentTwo from './components/ComponentTwo.vue'
import ComponentThree from './components/ComponentThree.vue'

export default {
  name: 'App',
  components: {
    ComponentTwo,ComponentThree
  }
}
</script>

<style>

</style>
