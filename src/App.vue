<template>
  <v-app>
    <HeaderComponet />
    <v-main>
      <HelloWorld />
    </v-main>
    <FooterComponet />
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import HeaderComponet from "./components/header/HeaderComponent.vue";
import FooterComponet from "./components/footer/FooterComponent.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
    // eslint-disable-next-line vue/no-unused-components
    HeaderComponet,
    // eslint-disable-next-line vue/no-unused-components
    FooterComponet,
  },

  data: () => ({
    //
  }),
};
</script>
