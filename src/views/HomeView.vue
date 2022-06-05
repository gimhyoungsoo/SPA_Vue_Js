<template>
  <div class="home">
    <img id="profile" alt="profile" src="../assets/profile.png">
    <img alt="Vue logo" src="../assets/logo.png">
    <h2>본 사이트는 node.js를 활용한 SPA 웹 사이트입니다.</h2>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style scoped>
  #profile{
    width: 20vw;
    border-color: black;
  }
  img{

    width: 10vw;
  }
</style>