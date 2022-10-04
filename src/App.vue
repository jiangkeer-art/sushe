<template>
  <div id="app" >
    <router-view/>
  </div>
</template>

<script>
import Login from "@/views/Login";
export default {
  name: 'app',
  components: {
    Login,
  }

}
</script>

<style>
#app{
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: -8px -8px auto;
}
</style>
