<template>
  <div class="base">
    <el-row>
      <el-col
      :span=12>
       <el-input type="textarea" :rows=10 placeholder="input something..." v-model="textarea"> </el-input>
      </el-col>
<el-button style="rign">base64</el-button>
     </el-row>
    <el-input type="textarea" :rows=10 placeholder="input something..." v-model="textarea"></el-input>
   
  </div>
</template>
<script>
export default {
  data() {
    return {
      textarea: ''
    };
  }
};
</script>

