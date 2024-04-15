<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <VApp>
    <VAppBar>
      
    </VAppBar>
  <v-navigation-drawer>
  <v-list-item title="My Application" subtitle="Vuetify"></v-list-item>
  <v-divider></v-divider>
  <v-list-item link title="List Item 1" to="/1"></v-list-item>
  <v-list-item link title="List Item 2" to="/bz"></v-list-item>
  <v-list-item link title="List Item 3" to="/ss/123"></v-list-item>
</v-navigation-drawer>
<VMain>
  <RouterView />
</VMain>

</VApp>

</template>
