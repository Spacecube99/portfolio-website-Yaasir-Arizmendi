<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>

    <div class="wrapper">
      <HelloWorld msg="Yaasir Arizmendi
      UX Designer & Front-End Developer" />
      <h3>
        To learn more about the services I can provide, click on the links below.
      </h3>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/contact">Contact</RouterLink>
        <RouterLink to="/skills">Skills</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

nav {
  width: 100%;
  font-size: 2rem;
  text-align: center;
  color: white;
}

nav a.router-link-exact-active:hover {
  color: white;
}

nav a:link {
  color: indigo;
}

nav a:visited {
  color: navy;
}

nav a:visited:hover {
  color: white;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}
</style>
