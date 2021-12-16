<template>
  <div id="app">
    <AppHeader />
    <Intro />
    <Features />
    <AppWrapper />
    <AppFooter />
    <router-view />
  </div>
</template>

<script>
// @ is an alias to /src
import AppHeader from "@/components/global/AppHeader.vue";
import Intro from "@/components/Intro.vue";
import Features from "@/components/Features.vue";
import AppWrapper from "@/components/apps/AppWrapper.vue";
import AppFooter from "@/components/global/AppFooter.vue";

export default {
  name: "app",
  components: {
    AppHeader,
    Intro,
    Features,
    AppWrapper,
    AppFooter,
  },
};
</script>
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
