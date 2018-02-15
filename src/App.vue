<template>
  <div id="app">
    <Header/>
    <ItemsList/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header";
import Footer from "./components/Footer";
import ItemsList from "./components/ItemsList";

export default {
  name: "App",
  components: {
    Header,
    ItemsList,
    Footer
  }
};
</script>

<style>

</style>
