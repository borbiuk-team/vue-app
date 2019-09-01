<template>
  <div class="app">
    <div class="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  <div id="main">

  </div>
  <footer>

  </footer>
  </div>
</template>
<style>

body {
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#main {
  height: 500px;
  position:relative;
	z-index:1;
}

footer {
  position:relative;
	z-index:-2;
}

</style>
