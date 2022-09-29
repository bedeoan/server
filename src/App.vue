<template>
  <div>
    <h1>
      Version: {{version}}
    </h1>
  </div>
</template>

<script>

export default {
  name: 'App',
  computed: {
    version() {
      return process.env.VUE_APP_VERSION
    }
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
  margin-top: 60px;
}
</style>
