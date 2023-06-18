<template>
  <section class="next-generation-section">
        <article class="next-generation-article">
          <h1>Next generation digital banking</h1>
          <p class="next-generation-text">
            Take your financial life online. Your Easybank account will be a
            one-stop-shop for spending, saving, budgeting, investing, and much
            more.
          </p>
          <Button />
        </article>
        <div class="next-generation-phones">
          <img
            src="../assets/images/image-mockups.png"
            alt="Phones with easybank app"
            class="next-generation-image"
          />
        </div>
      </section>
</template>

<script>

</script>

<style scoped>
.next-generation-section {
  display: flex;
  overflow: hidden;
}

.next-generation-article {
  display: flex;
  flex-direction: column;
  padding-top: 10rem;
  padding-left: 1rem;
}

h1 {
  font-size: 4rem;
  font-weight: 50;
  margin-bottom: 1rem;
}

.next-generation-text {
  margin-bottom: 1rem;
}

.next-generation-phones {
  width: 65%;
  background-image: url(../assets/images/bg-intro-desktop.svg);
  background-size: cover;
  background-repeat: no-repeat;
  margin-top: -8rem;
  padding-left: 14rem;
}

</style>