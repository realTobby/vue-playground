<template>
  <div id="app">
    <img alt="Vue logo" src="https://avatars.githubusercontent.com/u/24779607?s=400&u=dbcb6e3b012ee34756d114df139b5e62eb3a21b9&v=4">
    <HelloWorld msg="VueJS? Follow me on GitHub lol: github.com/realTobby"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
