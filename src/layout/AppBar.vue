<template lang="">
  <v-app-bar color="primary">
    <template #prepend>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
    </template>

    <v-app-bar-title><strong>Vue Playgroud</strong></v-app-bar-title>

    <template #append>
      <v-btn icon="mdi-dots-vertical"></v-btn>
    </template>
  </v-app-bar>
</template>
<script>
export default {
  name: "AppBar",
};
</script>
<style lang=""></style>
