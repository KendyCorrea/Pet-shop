<template>
  <nav>
     <router-link to="/">ANIMAUX ACCEPTE</router-link> |
    <router-link to="/Servicios">SERVICIOS</router-link> |
    <router-link to="/Tipo">TIPO DE MASCOTAS</router-link> |
     <router-link to="/Somos">QUINES SOMOS</router-link> |
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

            color: #2ea109;
            text-shadow: -2px 2px 4px rgba(0, 0, 0, 0.5),
                2px -2px 0 rgba(255, 255, 255, 0.9);
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2ea109;;
}

nav a.router-link-exact-active {
  color: #2ea109;;
}

button{
       color: #2ea109;
            text-shadow: -2px 2px 4px rgba(0, 0, 0, 0.5),
                2px -2px 0 rgba(255, 255, 255, 0.9);
                height: 50px;
}
*{
  margin: 15px;
}
</style>
