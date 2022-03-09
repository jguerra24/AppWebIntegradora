<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">MUTTER</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNavAltMarkup"
      aria-controls="navbarNavAltMarkup"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <router-link to="/" class="nav-item nav-link"> Inicio </router-link>
        <router-link to="/updates" class="nav-item nav-link">
          Actualizaciones
        </router-link>
        <router-link to="/about" class="nav-item nav-link">
          Sobre nosotros
        </router-link>
      </div>
    </div>
  </nav>
  <router-view />
</template>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css");
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
