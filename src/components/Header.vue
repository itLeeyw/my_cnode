<template>
    <div class="Header">
      <img src="../assets/cnodejs_light.svg" alt="logo">
      <ul>
        <li><a href="#">首页</a></li>
        <li><a href="#">新手入门</a></li>
        <li><a href="#">API</a></li>
        <li><a href="#">关于</a></li>
        <li><a href="#">注册</a></li>
        <li><a href="#">关于</a></li>
      </ul>
    </div>
</template>

<script>
    export default { // 向外默认配置一个配置对象
      name: "Header"
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.Header{
  background: #5a5555;
  height: 50px;
}
  img{
    max-width: 120px;
    margin-left: 50px;
    margin-top: 10px;
  }

  ul{
    list-style: none;
    float: right;
    margin: 4px;
  }

  li{
    display: inline-block;
    padding: 10px 15px;
  }
  
  a{
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
    text-shadow: none;
  }
</style>
