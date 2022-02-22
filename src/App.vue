<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <MainTop />
    <CardsCourses />
    <Book />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbotron from "./components/Jumbotron.vue";
import MainTop from "./components/MainTop.vue";
import CardsCourses from "./components/CardsCourses.vue";
import Book from "./components/Book.vue";

export default {
  name: "App",
  components: {
    Header,
    Jumbotron,
    MainTop,
    CardsCourses,
    Book,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss";
.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
