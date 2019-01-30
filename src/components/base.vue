<template>
  <div class="base">
    <el-input type="textarea" :row="10" placeholder="input something..." v-model="textarea"></el-input>
    <el-row></el-row>
  </div>
</template>
<script>
export default {
  data() {
    return {
      textarea: ""
    };
  }
};
</script>

