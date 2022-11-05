<template>
  <v-app>
    <v-main>
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import HeaderComponet from "./components/header/HeaderComponent.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
    // eslint-disable-next-line vue/no-unused-components
    HeaderComponet,
  },

  data: () => ({
    //
  }),
};
</script>
