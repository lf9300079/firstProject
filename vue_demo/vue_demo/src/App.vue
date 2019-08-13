<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!--3.使用该组件标签-->
    <HelloWorld1/>
   <!-- <router-view/>-->
  </div>
</template>

<script>
  // 1.引入组件
  import HelloWorld1 from './components/HelloWorld1'

export default {
  name: 'App',
  components: {
    //2.映射组件标签
    HelloWorld1
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
