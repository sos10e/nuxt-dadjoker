<template>
  <header>
    <ul id="navbar">
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/jokes">Jokes</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  data() {}
};
</script>

<style>
#navbar {
  display: none;
}
</style>
