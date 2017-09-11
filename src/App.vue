<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import 'src/plugins/jquery.min'
import 'src/plugins/jquery.fullPage'
export default {
  name: 'app',
  mounted(){
    $("h1").text("123");
  }
}
</script>

<style>
ul{
  list-style: none;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
