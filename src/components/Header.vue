<template>
  <header class="bannier padding-content">
      <img
        src="../assets/images/logo.svg"
        alt="Easybank's logo"
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
  margin-left: 8rem;
}

.logo-header {
  height: 1.5rem;
}

.ul-header > li {
  padding: 1rem;
}

</style>