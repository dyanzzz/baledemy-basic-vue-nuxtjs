<template>
  <div>
    <main v-if="$route.params.slug">
      <h1 v-text="'Detail Blog ' + $route.params.slug"></h1>
      <nuxt-link to="/blog">Back</nuxt-link>
    </main>
    <main v-else>
      <h1>List blog</h1>
      <nuxt-link to="/blog/1">Detail blog 1</nuxt-link> |
      <nuxt-link to="/blog/2">Detail blog 2</nuxt-link>
    </main>
  </div>
</template>



