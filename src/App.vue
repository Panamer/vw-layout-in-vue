<template>
  <div id="app">
    <helleWorld />
    <helloTwo />
    <helloThree />
  </div>
</template>

<script>
import '@/assets/scss/common.css'
import HelleWorld from '@/components/HelloWorld'
import HelloTwo from '@/components/HelloTwo'
import HelloThree from '@/components/HelloThree'

export default {
  name: 'App',
  components: {
    HelleWorld,
    HelloTwo,
    HelloThree
  }
}
</script>

<style>

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background: #fff
}
</style>
