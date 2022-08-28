<template>
  <nav>
     <router-link to="/">ANIMAUX ACCEPTE</router-link> |
    <router-link to="/Servicios">Servicios</router-link> |
    <router-link to="/Tipo de mascota">Tipo de mascota</router-link> |
     <router-link to="/QUINES SOMOS">QUINES SOMOS</router-link> |
      <router-link to="/CONTACTOS">CONTACTOS</router-link> |

  </nav>
  <router-view/>
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
  color: black;
}
</style>
