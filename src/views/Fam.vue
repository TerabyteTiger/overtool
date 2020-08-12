<template>
  <div class="about">
    <h1>Hey, friend! I'm glad you're here 💕</h1>
    <p>
      No matter what anyone else says, I'm proud of you. You crushed it when you
      used React/Vue/Svelte/Ember/Angular/Framework of your choice here.
    </p>
    <p>
      Don't judge a project's success by if some rando online says it's good or
      not. The important thing is if you accomplished something. Maybe you
      learned something new. Maybe your new tool saves you 5 minutes once some
      time in the future. Or maybe you just enjoyed yourself for a bit.
    </p>
    <h2>That's a win!!</h2>
    <p>
      And small wins build to big wins.
    </p>
    <p>
      I look forward to seeing what you accomplish 💕
    </p>
    <p>
      And just to spite the haters, here's a message loaded from Vuex Store
      (which some would call "overkill"):
    </p>
    <blockquote>
      {{ this.$store.state.msgForTheFam }}
    </blockquote>
    <p>
      Maybe someday we can throw a super chill pizza party or something 🍕🍕
    </p>
  </div>
</template>
<script>
export default {
  name: "Fam",
};
</script>

<style></style>
