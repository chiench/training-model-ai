<template>
  <v-app-bar
    elevation="7"
    app
    light
    color="white"
    elevate-on-scroll
    style="padding: 0 100px"
  >
    <v-toolbar-title>Web Vuetify</v-toolbar-title>
    <v-spacer />
    <v-list>
      <v-list-item-group class="d-flex justify-space-around">
        <v-list-item v-for="(item, i) in items" :key="i">
          <v-list-item-content>
            {{ item.tilte }}
          </v-list-item-content>
        </v-list-item>
        <v-btn outlined elevation="2"><v-icon>mdi-magnify</v-icon></v-btn>
      </v-list-item-group>
    </v-list>
  </v-app-bar>
</template>

<script>
export default {
  name: "HeaderComponet",
  data: () => ({
    items: [
      { tilte: "Home", link: "#" },
      { tilte: "About", link: "#" },
      { tilte: "Shop", link: "#" },
      { tilte: "Contact", link: "#" },
      { tilte: "Help", link: "#" },
    ],
  }),
};
</script>

<style scoped>
a {
  text-decoration: none;
}
</style>
