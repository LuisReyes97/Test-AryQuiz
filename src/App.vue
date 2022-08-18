<template>

  <!--Nav-bar-->
<nav class="navbar navbar-expand-lg  navbar-dark bg-primary">
  <div class="container-fluid">
     <a class="navbar-brand" href="#">
      <img src="../src/assets/latido-del-corazon.png" alt="" width="30" height="30">
    </a>

    <a class="navbar-brand" href="/">Arry</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarScroll">

    </div>
  </div>
</nav>


  <!--Nav-bar-->

 <nav class="navbar navbar_inverse navbar_inverse">
    <router-link to="/">Inicio</router-link> |
    <router-link to="/about">Aryy</router-link>
  </nav>

  <router-view />
</template>

<style>
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
  color: #42b983;
}
</style>
