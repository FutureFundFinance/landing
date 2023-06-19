<template>
   <section>
        <h2 class="latest-title"></h2>
        <div class="div-latest">
          <article class="latest-article">
            <img
              src=""
              alt=""
              class="latest-image"
            />
            <div class="latest-intro-article">
              <p class="latest-autor"></p>
              <h3 class="latest-article-title">
                
              </h3>
              <p class="latest-text">
                
              </p>
            </div>
          </article>
          <article class="latest-article">
            <img
              src=""
              alt=""
              class="latest-image"
            />
            <div class="latest-intro-article">
              <p class="latest-autor"></p>
              <h3 class="latest-article-title">
                
              </h3>
              <p class="latest-text">
                
              </p>
            </div>
          </article>
          <article class="latest-article">
            <img
              src=""
              alt=""
              class="latest-image"
            />
            <div class="latest-intro-article">
              <p class="latest-autor"></p>
              <h3 class="latest-article-title">
                
              </h3>
              <p class="latest-text">
                
              </p>
            </div>
          </article>
          <article class="latest-article">
            <img
              src=""
              alt=""
              class="latest-image"
            />
            <div class="latest-intro-article">
              <p class="latest-autor"></p>
              <h3 class="latest-article-title">
                
              </h3>
              <p class="latest-text">
                
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
  /*width: 256px;
  height: 200px;*/
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