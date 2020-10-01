<template>
  <nav>
    <v-toolbar flat class="grey lighten-4">
      <v-toolbar-title>
        <span class="font-weight-light">Todo</span>
        <span>Ninja</span>
      </v-toolbar-title>
      <v-spacer class="hidden-sm-and-down"></v-spacer>
      <v-btn depressed small>
        <span class="text-lowercase">Logout</span>
        <v-icon small right>exit_to_app</v-icon>
      </v-btn>
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
    </v-toolbar>
    <v-navigation-drawer app v-model="drawer" class="purple">
      <p class="white--text">test</p>
    </v-navigation-drawer>
  </nav>
</template>
<script>
export default {
  data() {
    return {
      drawer: false,
    };
  },
};
</script>
