<template>
  <div class="login-container">
    {{ msg }}
  </div>
</template>

<script>
  export default {
    name: 'Login',
    data() {
      return {
        msg: "Welcome to Your Vue.js App"
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  login-container {
    
  }
</style>
