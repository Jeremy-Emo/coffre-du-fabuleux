<template>
  <v-app>
    <v-app-bar app>
      <Header />
    </v-app-bar>

    <Nuxt />

    <v-footer app>
      <Footer />
    </v-footer>
  </v-app>
</template>

<script>
import Header from "../components/layout/my-header";
import Footer from "../components/layout/my-footer";

export default {
  components: {Footer, Header}
}
</script>
