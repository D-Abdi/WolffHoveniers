<template>
  <NavBar />
  <Home />
  <Footer />
</template>

<script>
import Home from "@/pages/Home/Home";
import NavBar from "@/components/NavBar";
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    NavBar,
    Home,
    Footer,
  }
}
</script>

<style>
@import "./styles/master.css";

body {
  width: 100%;
  overflow-x: hidden;
  background-color: #f8f8f8;
}
</style>
