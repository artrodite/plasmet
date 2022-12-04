<template>
  <Header></Header>
  <router-view />
  <Contact></Contact>
  <Footer></Footer>
</template>

<script setup>
import Header from "./components/Header.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Catamaran:wght@300;400;500;700;900&display=swap");
@import "./style/_variables.scss";
@import "./style/_scrollbar.scss";

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100vw;
  min-height: 100vh;
  overflow-y: scroll;
  overflow-x: hidden;
  font-family: "Catamaran", sans-serif;
  background: linear-gradient(180deg, #1b2740 0%, #030814 100%);
  color: $light-text-color;
  scroll-behavior: smooth;
}

a {
  text-decoration: none;
  color: inherit;
}

ul {
  list-style: none;
}
</style>
