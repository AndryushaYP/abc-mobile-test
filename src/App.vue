<template>
  <div id="app">
    <Header />
    <MainQuestion />
  </div>
</template>

<script>
import Header from "@/components/Header/Header.vue";
import MainQuestion from "@/components/MainQuestion/MainQuestion.vue";
export default {
  name: "App",
  components: { Header, MainQuestion },
};
</script>

<style>
#app {
  display: flex;
  flex-direction: column;
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgba(255, 255, 255, 0.6);

  box-sizing: border-box;

  --default-color: rgba(255, 255, 255, 0.6);
  --primary-fs: 25px;
  --small-fs: 16px;
}
body {
  width: 100%;
  padding: 0 284px 0 196px;
  background-color: #202024;
}
* {
  margin: 0;
  box-sizing: border-box;
}
</style>
