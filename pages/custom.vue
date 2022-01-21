<template>
  <div>
    <h2>Custom page - 1 attempt</h2>
    <NuxtLink to="/">Home page</NuxtLink>
    <hr />
    <ul>
      <li v-for="id in 5" :key="id">
        <NuxtLink :to="{ name: 'users-id', params: { id: id } }">
          user detail {{ id }}</NuxtLink
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'CustomPage',
  layout: 'custom',
}
</script>
