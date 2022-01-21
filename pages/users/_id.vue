<template>
  <div>
    <h1 v-if="$route.params.id == 1">ZABAK LADIK</h1>
    <h2>User - I´m user with id {{ $route.params.id }}</h2>

    <NuxtLink to="/custom">Back</NuxtLink>

    <hr />
  </div>
</template>

<script>
export default {
  name: 'UserPageId',
  layout: 'custom',
}
</script>
