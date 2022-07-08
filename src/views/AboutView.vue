<template>
  <div class="about">
    <h1>This is an about page</h1>
    <el-button @click="sunmit">按钮</el-button>
    <el-table :data="dataList" style="width: 100%">
      <el-table-column prop="prop" label="姓名" width="width"></el-table-column>
      <el-table-column prop="prop" label="年龄" width="width"></el-table-column>
      <el-table-column prop="prop" label="爱好" width="width"></el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"></el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"></el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"></el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"></el-table-column>
      <el-table-column prop="prop" label="籍贯" width="width"></el-table-column>
    </el-table>
    <el-button type="primary">buttonCont</el-button>
  </div>
</template>

<script>
export default {
  name: 'AboutView',
  data() {
    return {
      dataList: [],
      isture: 'ture',
      br: true,
    };
  },
  watch: {
    dataList: {
      handler(val, oldval) {
        console.log(val, oldval);
      },
    },
    isture: {
      handler(val) {
        console.log(val);
      },
    },
  },
  methods: {
    sunmit() {
      const a = 123;
      console.log(a);
      console.log('aaaaa');
      if (this.isture) {
        this.br = true;
      } else {
        this.br = false;
      }
    },
  },
};
</script>
