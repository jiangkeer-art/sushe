<template>
  <div class="main">
    <div class="left">
      <h3>------------------------------------------------------------------------</h3>
      基于springboot和vue的宿舍管理系统
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
  data() {
    return {}
  }
}
</script>

<style scoped>
.main {
  width: 100%;
  height: 90%;
  display: flex;
}

.left {
  width: 300px;
  height: 100%;
  overflow-y: auto;
}

.right {
  flex: 1;
  height: 100%;
  overflow-y: auto;
  border-radius: 20px;
  background-image: linear-gradient( 135deg, #EE9AE5 10%, #5961F9 100%);
}

.img{
  width:300px;
  height:400px;
}

</style>