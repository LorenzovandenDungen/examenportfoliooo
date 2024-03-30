<template>
  <header class="header">
    <nav>
      <ul class="nav-links">
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/websites">Websites</router-link></li>
        <li><router-link to="/tarieven">Tarieven</router-link></li>
        <li><router-link to="/contact">Contact</router-link></li>
        <li><router-link to="/offerte">Offerte</router-link></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
.header {
  border-bottom: 1px solid #000;
}

.nav-links {
  display: flex;
  justify-content: space-evenly;
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.nav-links a {
  text-decoration: none;
}
</style>
