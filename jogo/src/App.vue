<template>
  <div id="app">
    <div id="nav">
          <b-navbar type="dark" variant="dark">
    <b-navbar-nav>
      <b-nav-item href="/">Home</b-nav-item>
      <b-nav-item href="/about">About</b-nav-item>
      <b-nav-item href="/Profile">Profile</b-nav-item>
      <b-nav-item href="/Profiles">Profiles</b-nav-item>
    </b-navbar-nav>
  </b-navbar>

      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/Profile">Profile</router-link>  -->
    </div>
    <router-view/>

  </div>

</template>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0e0e0e;
}

#nav {
  padding: 30px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>