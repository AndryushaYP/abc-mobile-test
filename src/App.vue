<template>
  <div id="app">
    <Header />
    <MainQuestion />
    <Request />
  </div>
</template>

<script>
import Header from "@/components/Header/Header.vue";
import MainQuestion from "@/components/MainQuestion/MainQuestion.vue";
import Request from "@/components/Request/Request.vue";
export default {
  name: "App",
  components: { Header, MainQuestion, Request },
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
  --gold-color: #f6c866;
  --primary-fs: 25px;
  --small-fs: 16px;
}
body {
  width: 100%;
  padding: 0 284px 0 196px;
  background-color: #202024;
  background-image: url(./assets/blik1920.png);
  background-repeat: no-repeat;
  background-position: top right;
  background-size: cover;
}
* {
  margin: 0;
  box-sizing: border-box;
}
</style>
