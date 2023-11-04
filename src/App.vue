<script setup>
import { RouterView } from "vue-router";
</script>

<template>
  <v-app>
    <v-main class="text-center">
      <v-container fluid>
        <RouterView />
      </v-container>
    </v-main>
  </v-app>
</template>

<style scoped>

#app {
  display: initial !important;
}


</style>
