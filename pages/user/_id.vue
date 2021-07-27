<template>
  <div>
    <h1>profile {{ $route.params.id }}</h1>
    <nuxt-link to="/user">Back</nuxt-link>
  </div>
</template>

<script>
export default {
  validate({ params }) {
    return /^\d+$/.test(params.id)
  }
}
</script>
