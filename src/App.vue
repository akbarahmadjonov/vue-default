<template>
  <div id="app">
    <Header />
    <Service />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/header.vue";
import Service from "./components/services.vue";
import Footer from "./components/footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Service,
    Footer,
  },
};
</script>

<style></style>
