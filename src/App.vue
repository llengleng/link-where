<template>
  <div>
    <el-container>
      <el-header class="header">
        <NavBar></NavBar>
      </el-header>
      <el-main>
        <HelloWorld msg="去你想去的地方"/>
      </el-main>
    </el-container>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NavBar
  }
}
</script>

<style>
@import "./assets/css/global.css";
.header {
  padding: 0;
}

</style>
