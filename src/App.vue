<template>
  <div id="app">
    <img alt="Vue logo" src="https://66.media.tumblr.com/7d50788be947ba85477cb801982b9598/tumblr_pei3joPjXU1uvsfoeo1_1280.png">
    <HelloWorld msg="Learn GO!!!!!!!"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
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

img {
  width: 300px;
}
</style>
