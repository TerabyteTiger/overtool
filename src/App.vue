<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/fam">I like this site</router-link> |
      <router-link to="/h8rs">I'm mad about this site existing</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

p {
  font-size: 1.5rem;
  max-width: 750px;
  margin: 1rem auto;
  line-height: 2rem;
}

h1 {
  font-size: 6em;
}

h2 {
  font-size: 3em;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

blockquote {
  font-size: 1.2rem;
  font-weight: bold;
  color: #5a5475;
}
</style>
