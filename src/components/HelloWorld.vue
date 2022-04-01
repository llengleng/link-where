<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      身体和灵魂必须有一个在路上
    </p>
    <h3>前端</h3>
    <ul>
      <li><a href="https://v3.cn.vuejs.org/" target="_blank" rel="noopener">Vue</a></li>
      <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/display" target="_blank" rel="noopener">MDN 文档</a></li>
    </ul>
    <h3>后端</h3>
    <ul>
      <li><a href="https://pdai.tech/" target="_blank" rel="noopener">Java 文档</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
