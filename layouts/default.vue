<template>
  <div>
    <h1>Default layout</h1>
    <Nuxt />
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout',
}
</script>

<style>
a {
  color: red;
}

body {
  max-width: 600px;
  margin: auto;
  padding: 1rem;
}

h1 {
  @apply text-4xl;
}

h2 {
  @apply text-2xl;
}

.page-enter-active,
.page-leave-active {
  transition: opacity 0.5s;
}
.page-enter,
.page-leave-active {
  opacity: 0;
}
</style>
