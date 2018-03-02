<template>
  <div id="app">
    <!-- <banner />
    <grid />
    <block />
    <list /> -->
    <helleWorld />
  </div>
</template>

<script>
import '@/assets/scss/common.css'
import HelleWorld from '@/components/HelloWorld'
import Banner from '@/components/Banner'
import Grid from '@/components/Grid'
import Block from '@/components/Block'
import List from '@/components/List'

export default {
  name: 'App',
  components: {
    HelleWorld,
    Banner,
    Grid,
    Block,
    List
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
