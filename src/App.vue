<template>
  <div class="app" id="app">
    <div id="nav" class="ml-auto" >
      <img alt="pokemon logo" width="50" src="https://pngimg.com/uploads/pokeball/pokeball_PNG19.png">   |
      <router-link to="/">Home</router-link> |
      <router-link to="/about">Desarrollo</router-link> |
      <router-link to="/fechas">Fechas importantes</router-link> |
      <router-link to="/evidencias">Evidencias</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
.app {
  background-color: #ABBAEA;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: justify;
  color: #2c3e50;
}

#nav {
  padding: 20px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
