<template>
  <div class="home">
    <h1>Welcome to OverTool</h1>
    <p>A website that easily could have been built with plain HTML/CSS</p>
    <p>but instead I used Vue 💚</p>
    <hr style="width: 25%;" />

    <p>
      This site is inspired by anyone that has ever commented something like
    </p>
    <blockquote>
      The amount of tooling people use to build a simple website infuriates me
    </blockquote>
    <p>or</p>
    <blockquote>
      You cannot learn React without knowing JavaScript first
    </blockquote>

    <h2>Built with:</h2>
    <p>
      <a href="https://vuex.vuejs.org/">
        Vuex
      </a>
      |
      <a href="https://router.vuejs.org/">
        Vue Router
      </a>
      |
      <a href="https://vuejs.org/">
        Vue
      </a>
      | <a href="https://github.com/wesbos/waait">Waait</a> | Love 💕 | & Hosted
      on <a href="https://www.netlify.com/">Netlify</a>
    </p>
    <p class="smol">It's also a pwa for your enjoyment 🤫</p>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
};
</script>

<style>
.smol {
  font-size: 0.8rem;
}
</style>
