<template>
  <header class="bannier padding-content">
      <img
        src="../assets/images/Logo_FutureFund_Blanco.png" 
        alt="Future Fund logo"
        class="logo-header"
      />
      <nav class="nav-header">
        <ul class="ul-header">
          <li>Home</li>
          <li>About</li>
          <li>Contact</li>
          <li>Blog</li>
          <li>Careers</li>
        </ul>
      </nav>
      <Button />
    </header>
</template>

<script>
import Button from "../components/Button.vue";
export default {
  name: "Header",
  components: {
    Button,
  },
};
</script>

<style scoped>
.bannier {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  margin-right: 8rem;
  /*margin-left: 8rem;*/
  background-color: #3f0a6e;
  width: 100%;
}

.logo-header {
  height: 3rem;
}

.ul-header > li {
  padding: 1rem;
}

</style>