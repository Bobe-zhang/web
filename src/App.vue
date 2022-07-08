<template>
  <div id="app">
    hahha
    <el-button type="primary">按钮</el-button>
    <el-button type="success">按钮</el-button>
    <el-button type="error" @click="click">按钮</el-button>
    <router-view></router-view>
  </div>
</template>
 <script>
 export default {
   data(){
     return {}
   },
   methods:{
     click() {
       this.$router.push({
         path:'/about'
       })
     }
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
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

</style>
