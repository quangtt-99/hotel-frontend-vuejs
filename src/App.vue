<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
html, body {
  margin: 0;
  height: 100%;
  /* overflow-x: hidden; */
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
