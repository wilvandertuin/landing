<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="css">
* {
  box-sizing: border-box;
}

body {
  background-color: rgb(225,233,227);
  font-family: 'Fira Mono', monospace;
  margin: 0;
  padding: 0;
}
</style>
