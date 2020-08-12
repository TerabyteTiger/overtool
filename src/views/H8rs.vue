<template>
  <main>
    <div v-if="waitFlag">
      <h1>So you're {{ bigMad }}, huh? 😠</h1>
      <p>
        Probably thinking,
        <strong
          >"wOw, this scrub doesn't even know how to put together a simple HTML
          page!"</strong
        >
      </p>
      <p>
        Well, you're right.
      </p>
      <p>
        I've never built a site with pure HTML, CSS, and vanilla™ JavaScript in
        my life.
      </p>
      <p>
        And if it is up to me, probably never will. Frameworks are way too cool.
      </p>
      <p>
        And since I know you're wondering - yes, the following message is
        loading from the store:
      </p>
      <blockquote>
        {{ this.$store.state.msgForTheH8rs }}
      </blockquote>
    </div>
    <div v-else>
      <h2>
        Please Wait ...
      </h2>
      <p>The page is loading</p>
    </div>
  </main>
</template>

<script>
import wait from "waait";
export default {
  name: "ThisOneIsForYou",
  data() {
    return {
      bigMad: "big mad",
      waitFlag: false,
    };
  },
  async mounted() {
    await wait(2000);
    this.waitFlag = true;
  },
};
</script>

<style></style>
