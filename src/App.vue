<template>
  <div id="app">
    <GlobalHeader />
    <router-view />
    <footer class="footer">
      Footer
    </footer>
  </div>
</template>

<script>
// Import your GlobalHeader component
import GlobalHeader from "./components/GlobalHeader.vue";

export default {
  name: 'App',
  components: {
    GlobalHeader
  }
}
</script>

<style>
/* Global styles */
.footer {
  border-top: 1px solid #000;
  text-align: center;
  padding: 1rem;
  margin-top: auto; /* If using Flexbox or Grid on #app */
}
</style>
