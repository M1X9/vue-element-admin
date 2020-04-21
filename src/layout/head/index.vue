<template>
  <div>
   <el-menu class="el-menu-demo" mode="horizontal" background-color="#334157" text-color="#fff" active-text-color="#fff">
    <el-button class="buttonimg">
      <img class="showimg" :src="collapsed?imgsq:imgshow" @click="toggle(collapsed)">
    </el-button>
   </el-menu>
  </div>
</template>
<script>
export default {
  name: "header",
  data() {
    return {

    }
    
  },
  
  
};
</script>
<style scoped>

</style>