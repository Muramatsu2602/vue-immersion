<template>
 
  <div id="nav">
    <router-link to="/">Home </router-link> |
    <router-link to="/about">About </router-link> |
    <router-link to="/components">Components </router-link>
  </div>

  <!-- CREATE AN HEADER BEFORE ROUTER VIEW TO PRESERVE ITS LAYOUT WHEN TRANSITIONING THROUGH PAGES -->
  <router-view />
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    margin: 0.5rem;
    text-decoration: none;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

.negrito {
  font-weight: bold;
  font-size: 50px;
}
</style>
