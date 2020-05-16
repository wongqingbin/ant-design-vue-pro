<template>
  <div class="home">
    <div class="banner">
      <img alt="Vue logo" style="width: 64px; height: 64px" src="../assets/logo.png">
      <h3 style="margin-top: 1rem">Welcome to Your Vue.js App</h3>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Home',
  data () {
  },
  created () {
  },
  methods: {
  }
}
</script>

<style scoped>
  .home {
    width: 900px;
    margin: 0 auto;
    padding: 25px 0;
  }
  .home > .banner {
    text-align: center;
    padding: 25px 0;
    margin: 25px 0;
  }
</style>
