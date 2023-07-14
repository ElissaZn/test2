<template>
    <div>
      <h1>User Page</h1>
      <p>Username: {{ username }}</p>
      <p>Address: {{ address }}</p>
    </div>
  </template>
  <script setup lang="ts">
   
  const props = defineProps({
      username: String,
      address: String,
  })
  </script>