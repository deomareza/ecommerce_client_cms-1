<template>
  <div id="app">
    <div id="nav">
      <!-- <router-link to="/login">Login</router-link> |
      <router-link to="/">Home</router-link> |
      <router-link to="/product-add">Add Product</router-link> -->
      <!-- <router-link to="/about">About</router-link> -->
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Hello there General Kenobi'
    }
  },
  components: {
  },
  created () {
    // const accessToken = localStorage.getItem('access_token')
    // if (!accessToken) {
    //   this.$router.push({ name: 'Login' })
    // } else {
    //   this.$router.push({ name: 'Home' })
    // }
  }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
