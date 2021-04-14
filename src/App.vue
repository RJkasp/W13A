<template>
  <div id="app">
    <!-- page cant be empty or the compiler in vue will hit you with an error so we need to make sure theres something in the components when connecting -->
     <page-header></page-header>
    <page-body></page-body>
    <img alt="Vue logo" src="./assets/logo.png">
    <page-footer></page-footer>
   
  </div>
</template>

<script>
//imports the components to app.vue app.vue is like the main page
import PageHeader from "./components/PageHeader.vue";
import PageBody from "./components/PageBody.vue";
import PageFooter from "./components/PageFooter";
export default {
  name: 'App',
  components: {
    // I think this section connects the component defaults inside each component.
    PageHeader,
    PageBody,
    PageFooter,
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  }
</style>
