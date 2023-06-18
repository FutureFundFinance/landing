<template>
   <section>
        <h2 class="latest-title">Latest Articles</h2>
        <div class="div-latest">
          <article class="latest-article">
            <img
              src="../assets/images/image-currency.jpg"
              alt=""
              class="latest-image"
            />
            <div class="latest-intro-article">
              <p class="latest-autor">By Claire Robinson</p>
              <h3 class="latest-article-title">
                Receive money in any currency with no fees
              </h3>
              <p class="latest-text">
                The world is getting smaller and we’re becoming more mobile. So
                why should you be forced to only receive money in a single …
              </p>
            </div>
          </article>
          <article class="latest-article">
            <img
              src="../assets/images/image-restaurant.jpg"
              alt=""
              class="latest-image"
            />
            <div class="latest-intro-article">
              <p class="latest-autor">By Wilson Hutton</p>
              <h3 class="latest-article-title">
                Treat yourself without worrying about money
              </h3>
              <p class="latest-text">
                Our simple budgeting feature allows you to separate out your
                spending and set realistic limits each month. That means you …
              </p>
            </div>
          </article>
          <article class="latest-article">
            <img
              src="../assets/images/image-plane.jpg"
              alt=""
              class="latest-image"
            />
            <div class="latest-intro-article">
              <p class="latest-autor">By Wilson Hutton</p>
              <h3 class="latest-article-title">
                Take your Easybank card wherever you go
              </h3>
              <p class="latest-text">
                We want you to enjoy your travels. This is why we don’t charge
                any fees on purchases while you’re abroad. We’ll even show you …
              </p>
            </div>
          </article>
          <article class="latest-article">
            <img
              src="../assets/images/image-confetti.jpg"
              alt=""
              class="latest-image"
            />
            <div class="latest-intro-article">
              <p class="latest-autor">By Claire Robinson</p>
              <h3 class="latest-article-title">
                Our invite-only Beta accounts are now live!
              </h3>
              <p class="latest-text">
                After a lot of hard work by the whole team, we’re excited to
                launch our closed beta. It’s easy to request an invite through
                the site ...
              </p>
            </div>
          </article>
        </div>
      </section>
</template>

<script>

</script>

<style scoped>


.div-latest {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  width: 92%;
}

.latest-title {
  margin-bottom: 5rem;
}

.latest-article {
  display: flex;
  flex-direction: column;
}

.latest-image {
  width: 256px;
  height: 200px;
}

.latest-intro-article {
  width: 80%;
  padding: 1.5rem;
  font-size: 0.9em;
}

.latest-autor,
.latest-article-title,
.latest-text {
  margin: 0.5rem;
}

</style>