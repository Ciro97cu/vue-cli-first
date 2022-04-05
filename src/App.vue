<template>
  <div id="app">
    <MainTitle msg="La mia prima app con Vue CLI!" />
    <JumboTron />
  </div>
</template>

<script>
import MainTitle from "./components/MainTitle.vue";
import JumboTron from "./components/JumboTron.vue";

export default {
  name: "App",
  components: {
    MainTitle,
    JumboTron,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #5f0583;
  margin-top: 60px;
}
</style>
