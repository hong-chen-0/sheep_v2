<template>
  <div class="title">牛了个牛</div>
  <HelloWorld msg="Welcome"/>
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
  background: url('./assets/glass.jpg') no-repeat center / cover;
  height: 100vh;
  width: 100%;
  padding: 0;
  margin: 0;
}
.title{
  color: black;
  text-shadow: 2px 2px 1px white;
  font-size: 40px;
  font-weight: bold;
  padding: 50px;
}
</style>
