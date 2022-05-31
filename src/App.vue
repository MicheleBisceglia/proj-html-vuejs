<template>
  <div id="app">
    <AppHeader @searchClick="search"/>
    <AppMain />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";
export default {
  name: "App",
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
  methods: {
    search(searchKey) {
      console.log(searchKey);
    }
  }
}
</script>

<style lang="scss">
@import "./style/common.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100vh;
}
</style>
