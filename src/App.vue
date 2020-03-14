<template>
  <div id="app">
    <img class="logo" src="https://tva1.sinaimg.cn/large/006tNbRwgy1gb0uax9igwj31400u00vl.jpg">
    <!-- <HelloWorld/> -->
    <h1>我命由我不由天</h1>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
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
.logo {
  width: 100px;
  height: 100px;
}
</style>
