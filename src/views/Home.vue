<template>
  <div id="home" class="bg-image d-flex align-items-center">
    <div class="container text-center" style="padding-bottom: calc(15%);">
      <h1 class="mb-4">The Burgess Lab</h1>
      <h4 class="mb-5">Organic and Medicinal Chemistry</h4>
      <p>
        <router-link
          to="/rgroup/burgess/research"
          class="btn btn-lg btn-outline-light ms-2 me-2"
          style="height: 50px;"
        >
          Our research
        </router-link>
        <router-link
          to="/rgroup/burgess/contact"
          class="btn btn-lg btn-outline-light ms-2 me-2"
          style="height: 50px;"
        >
          Get in touch
        </router-link>
        <a
          href="https://twitter.com/kevinburgesslab?lang=en"
          class="btn btn-lg btn-primary d-inline-flex align-items-center justify-content-center ms-2 me-2"
          style="width: 275px; height: 50px;"
        >
          <div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="32"
              height="32"
              fill="currentColor"
              class="bi bi-twitter"
              viewBox="0 0 16 16"
            >
              <path
                d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"
              />
            </svg>
          </div>
          <div class="ms-3">Follow us on Twitter</div>
        </a>
      </p>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
  components: {}
});
</script>

<style scoped>
#home {
  height: calc(100vh - 56px);
  background-color: #333;
  color: #fff;
}

h1,
h4 {
  font-family: "Raleway", sans-serif;
  font-weight: 700;
}

h1 {
  font-size: 4rem;
}

.bg-image {
  background: linear-gradient(rgba(20, 20, 20, 0), rgba(20, 20, 20, 0.8)),
    url("../../public/bg-2.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
}
</style>
