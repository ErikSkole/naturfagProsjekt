<template>
  <nav>
    <div class="navbar">
      <router-link to="/">Hjem</router-link>
      <router-link to="/info">Info</router-link>
      <router-link to="/kontakt">Kontakt</router-link>
    </div>
  </nav>
  <main>
    <router-view/>
  </main>
</template>

<style>
.navbar {
  display: flex;
  justify-content: center;
  border-bottom: 1px solid black;
  width: fit-content;
  justify-self: center;
}

nav {
  display: flex;
  justify-content: center;
}

nav a {
  background-color: white;
  color: black;
  text-decoration: none;
  padding: 1rem;
  border-radius: 10px;
  font-size: 30px;
  margin: 1rem;
}

nav a.router-link-exact-active {
  background-color: rgb(59, 105, 255);
  color: white;
}
</style>
