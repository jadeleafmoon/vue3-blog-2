<template>
  <nav>
    <router-link to="/">Home</router-link>
  </nav>
  <router-view/>
</template>

<style>

body {
  background-color: #D9AFD9;
  background-image: linear-gradient(0deg, #D9AFD9 0%, #97D9E1 100%);
  background-attachment: fixed;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  /* color: white; */
}
</style>
