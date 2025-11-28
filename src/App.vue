<template>
  <div>
    <nav>
      <router-link to="/">Inicio</router-link> |
      <router-link to="/about">Sobre nosotros</router-link> |
      <router-link to="/contact">Contacto</router-link>
    </nav>
    <hr />
    <router-view />
  </div>
</template>

<style>
nav {
  background: #42b883;
  padding: 1rem;
}
nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}
nav a.router-link-exact-active {
  font-weight: bold;
  text-decoration: underline;
}
</style>