<template>
  <div>
    <el-container>
        <el-aside class="side" width="260px">
          <NavBar></NavBar>
        </el-aside>
        <el-container>
          <el-header class="header">
            <h1>"给你的努力一个交代，挥出已经紧握在双拳中的梦想" ——原创 • 柠檬盐</h1>
          </el-header>
          <el-main>
            <HelloWorld/>
          </el-main>
        </el-container>   
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
    NavBar,
  },
}
</script>

<style>
@import "./assets/css/global.css";
.side {
  height: 720px;
  border-right: 1px solid rgb(227, 222, 222);
}
.el-menu {
  border-right: none;
}
.header {
  padding: 0;
  border-bottom: 1px solid rgb(227, 222, 222);
  display: flex;
  justify-content: center;
  align-items: center;
  color: #79aeeb;
}
</style>
