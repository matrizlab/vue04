<template>
  <div id="app">
    <!-- <FormComponent /> -->
    <!-- <Home /> -->
    <!-- <Tabs /> -->
    <!-- <Layout /> -->
    <!-- <Popovers /> -->
    <!-- <Scrollspy /> -->
    <Tooltip />
  </div>
</template>

<script>
// import FormComponent from "./components/FormComponent.vue";
// import Home from "./components/Home.vue";
// import Tabs from "./components/Tabs.vue";
// import Layout from "./components/Layout.vue";
// import Popovers from "./components/Popovers.vue";
// import Scrollspy from "./components/Scrollspy.vue";
import Tooltip from "./components/Tooltip.vue";

export default {
  name: "app",
  components: {
    // FormComponent,
    // Home,
    // Tabs,
    // Layout,
    // Popovers,
    // Scrollspy,
    Tooltip
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
