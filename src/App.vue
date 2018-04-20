<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
body {
  margin: 0;
  background-color: #eeeeee;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.page-container {
  background-color: white;
  min-height: 100vh;
}

@media only screen and (min-width: 600px) {
  .page-container {
    width: 60%;
    margin-left: 16.6%;
  }
}

</style>
