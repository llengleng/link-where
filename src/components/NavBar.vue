<template>
    <div class="nav-bar">
      <el-row class="tac">
        <h1>链接</h1>
      <el-col >
        <el-menu
          @open="handleOpen"
          @close="handleClose"
        >
          <el-sub-menu index="1">
            <template #title>前端</template>
            <el-menu-item index="1-1">学习网站</el-menu-item>
            <el-menu-item index="1-2">文档网站</el-menu-item>
            <el-menu-item index="1-3">item one</el-menu-item>
          </el-sub-menu>
          <el-sub-menu index="2">
            <template #title>后端</template>
            <el-menu-item index="2-1">item one</el-menu-item>
          </el-sub-menu>
          <el-sub-menu index="3">
            <template #title>数据结构与算法</template>
            <el-menu-item index="3-1">item one</el-menu-item>
          </el-sub-menu>
          <el-sub-menu index="4">
            <template #title>计算机网络</template>
            <el-menu-item index="4-1">item one</el-menu-item>
          </el-sub-menu>
          <el-sub-menu index="5">
            <template #title>Linux</template>
            <el-menu-item index="5-1">学习网站</el-menu-item>
          </el-sub-menu>
          <el-sub-menu index="6">
            <template #title>面试</template>
            <el-menu-item index="6-1">八股文</el-menu-item>
          </el-sub-menu>
          <el-sub-menu index="7">
            <template #title>设计</template>
            <el-menu-item index="7-1">图标库</el-menu-item>
            <el-menu-item index="7-2">制图网站</el-menu-item>
          </el-sub-menu>
        </el-menu>
      </el-col>
    </el-row>
    </div>
</template>

<script>
import '@element-plus/icons-vue';
export default {
  name: 'NavBar',
}

</script>

<style>
@import "../assets/css/navbar.css";
.tac {
  display: flex;
  text-align: center;
  justify-content: center;
  justify-items: center;
}
h1 {
  margin: 10px;
}

</style>