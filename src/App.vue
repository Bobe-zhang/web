<template>
  <div id="app">
    hahha
    <el-button type="primary">按钮</el-button>
    <el-button type="success">按钮</el-button>
    <el-button type="error">按钮</el-button>
    <el-table :data="data" style="width: 100%">
      <el-table-column prop="prop" label="姓名" width="width"> </el-table-column>
      <el-table-column prop="prop" label="年龄" width="width"> </el-table-column>
      <el-table-column prop="prop" label="爱好" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
    </el-table>
  </div>
</template>

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

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
