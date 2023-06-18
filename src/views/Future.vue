<template>
  <div>
    <Header />
    <main class="padding-content">
      <NextGeneration />
      <Why />
      <Articles />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import NextGeneration from "../components/NextGeneration"
import Why from "../components/Why.vue" 
import Articles from "../components/Articles.vue"
import Footer from "../components/Footer.vue"
export default {
  name: "Easybank",
  components: {
    Header,
    NextGeneration,
    Why,
    Articles,
    Footer
  },
};
</script>

<style scoped>
.padding-content {
  padding-left: 8rem;
}
</style>
