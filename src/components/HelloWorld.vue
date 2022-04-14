<template>
  <div class="root-box">  
    <div class="hello">
      <el-card class="box-card" v-for="o in 11" :key="o">
        <div class="card">
          <div class="card-img">
            <img class="img" src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png">
          </div>
          <div class="text">
            <div class="title">Vue 官网</div>
            <div>简介：</div>
          </div>
        </div>
      </el-card>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<style scoped>
.hello {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.box-card {
  width: 330px;
  margin: 20px;
}
.card {
  display: flex;
}
.text {
  margin-left: 30px;
}
.title {
  margin-bottom: 20px;
}
.img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
}
</style>
