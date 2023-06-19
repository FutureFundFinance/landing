<template>
  <section class="next-generation-section">
        <article class="next-generation-article">
          <h1 class="Somos">Tu fondo de ahorro Web3</h1>
          <p class="next-generation-text">
            En Future Fund te ayudamos a hacer realidad tus sueños.
          </p>
          <p class="next-generation-text">
            Usamos tecnología Blockchain y Stablecoins para generar ingresos pasivos a mediano y largo plazo.
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
  padding-top: 18rem;
  padding-left: 1rem;
  font-size: 1rem;
}

.Somos {
  font-size: 3rem;
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