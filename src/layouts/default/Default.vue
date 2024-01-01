<template>
  <v-app>
    <nav>
      <RouterLink to="/vuetify">Home</RouterLink>
      <RouterLink to="/vuetify/about">About</RouterLink>
    </nav>
    <default-view />
  </v-app>
</template>

<script lang="ts" setup>
  import DefaultView from './View.vue'
</script>
