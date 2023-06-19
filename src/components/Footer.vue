<template>
  <footer class="padding-content">
      <div class="logo-emote-nav">
        <div class="logo-emote">
          <img src="../assets/images/Logo_FutureFund_Blanco.png" alt="" class="logo-footer" />
          <div class="emote-footer">
            <img
              src="../assets/images/icon-facebook.svg"
              alt="facebook's icon"
              class="one-emote-footer"
            />
            <img
              src="../assets/images/icon-youtube.svg"
              alt="youtube's icon"
              class="one-emote-footer"
            />
            <img
              src="../assets/images/icon-twitter.svg"
              alt="twitter's icon"
              class="one-emote-footer"
            />
            <img
              src="../assets/images/icon-pinterest.svg"
              alt="pinterest's icon"
              class="one-emote-footer"
            />
            <img
              src="../assets/images/icon-instagram.svg"
              alt="instagram's icon"
              class="one-emote-footer"
            />
          </div>
        </div>
        <nav>
          <ul class="ul-footer">
            <div class="ul-part-footer">
              <li>About us</li>
              <li>Contact</li>
              <li>Blog</li>
            </div>
            <div class="ul-part-footer">
              <li>Careers</li>
              <li>Support</li>
              <li>Privacy policy</li>
            </div>
          </ul>
        </nav>
      </div>
      <div class="button-easy-rights">
        <Button class="button-footer"/>
        <p class="text-easy-rights">© Future Fund CO. All Rights Reserved</p>
      </div>
    </footer>
</template>

<script>
import Button from "../components/Button.vue";
export default {
  name: "Footer",
  components: {
    Button,
  },
};
</script>

<style scoped>

footer {
  background-color: #2b074b; /*var(--font-color);*/
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-right: 8rem;
}

.logo-footer
  {height: 3rem;
  margin-top: 1rem;}
.emote-footer {
  margin: 2rem 1rem 2rem 0.5rem;
}

.logo-emote-nav {
  display: flex;
}

.logo-emote {
  display: flex;
  flex-direction: column;
}

.one-emote-footer {
  cursor: pointer;
  padding: 0.5rem;
  height: 2.5rem;
}

.ul-footer {
  display: flex;
  margin: 2rem;
  color: white;
}

.ul-part-footer {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  height: 8rem;
  margin-left: 4rem;
  margin-right: 4rem;
}

.button-easy-rights {
  text-align: right;
}

.text-easy-rights{
  margin-top: 1.5rem;
  padding-top: 1rem;
  font-size: 0.9em;
}
</style>