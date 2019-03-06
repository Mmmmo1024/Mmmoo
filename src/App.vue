<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
body{
  background: ghostwhite
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #582c0f;
  font-weight: bolder;
}
.baseLayout{
  width: 1000px;
  margin: auto;
  background: #fff;
  padding: 10px 20px;
  box-shadow: 0px 0px 50px #dcdcdc  
}
</style>
