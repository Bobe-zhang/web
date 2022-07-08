<template>
  <div class="about">
    <h1>This is an about page</h1>
    <el-table :data="data" style="width: 100%">
      <el-table-column prop="prop" label="姓名" width="width"> </el-table-column>
      <el-table-column prop="prop" label="年龄" width="width"> </el-table-column>
      <el-table-column prop="prop" label="爱好" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"> </el-table-column>
    </el-table>
  </div>
</template>

<script>
export default {
  name: 'AboutView',
  data() {
    return {
      data: [],
    };
  },
};
</script>
