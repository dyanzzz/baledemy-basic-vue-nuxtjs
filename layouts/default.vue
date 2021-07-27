<template>
  <div>
    <header>
      <nuxt-link to="/">Home</nuxt-link> |
      <nuxt-link to="/about">About</nuxt-link>  |
      <nuxt-link to="/contact">Contact</nuxt-link> |
      <nuxt-link to="/user">User</nuxt-link> |
      <nuxt-link to="/blog">Blog</nuxt-link>
    </header>

    <Nuxt/>

    <footer>
      <p>&copy; 2021 - Kelas NuxtJs</p>
    </footer>
  </div>
</template>

<style>
body {
  margin: 15%;
  color: salmon;
  text-align: center;
}
</style>
