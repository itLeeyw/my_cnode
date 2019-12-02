<template>
  <div id="app">
    <Header></Header>
    <div class="main">
      <router-view name="slidebar"></router-view>
      <router-view name="main"></router-view>
    </div>
  </div>
</template>

<script>
  import Header from "./components/Header"
  import PostList from "./components/PostList"
export default {
  name: 'App',
  components:{
    PostList,
    Header
  }
}
</script>
<style>
  #app{
    background: #e1e1e1;
  }
  .main{
    width: 80%;
    margin: 0 auto;
  }
</style>
