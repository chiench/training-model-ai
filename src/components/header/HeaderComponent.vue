<template>
  <v-app-bar height="100" app color="#424242" dark>
    <div style="width: 100%" class="d-flex justify-center align-center">
      <v-img
        alt="AI Logo"
        class="shrink mr-2 rounded-circle"
        contain
        src="../../assets/openai-avatar.png"
        transition="scale-transition"
        width="60"
      />

      <span class="text-h5 text-uppercase font-weight-medium mr-2">
        <strong>Predic Network </strong></span
      >
    </div>
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
