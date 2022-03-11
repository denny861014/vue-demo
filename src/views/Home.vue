<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <router-link to="/login">後台登入</router-link> |
    <router-link to="/user/cart">商品頁面</router-link>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  created () {
    console.log(process.env.VUE_APP_API, process.env.VUE_APP_PATH)
  }
}
</script>
