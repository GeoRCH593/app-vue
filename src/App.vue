<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/cards">Cards</router-link> |
    <router-link to="/forms">Forms</router-link> |
    <router-link to="/promos">Promos</router-link> |
    <router-link to="/about">About</router-link> 
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
  background-color: darkblue;
}

nav a {
  font-weight: bold;
  color: #ffffff;
  text-decoration: none;
  margin: 0 20px;
  transition: .5s;
}

nav a:hover{
  color: yellow;
}
nav a.router-link-exact-active {
  color: yellow;
}
</style>
