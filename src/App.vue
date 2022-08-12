<template>

  <AppHeader logo="Alfa-Streams"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <New name="Dr Ali Hasan"/>
</template>

<script>
import AppHeader from "./components/AppHeader";
import HelloWorld from './components/HelloWorld.vue';
import New from './components/New'


export default {
  name: 'App',

  components: {
    HelloWorld,
    New,
    AppHeader

  }
}
</script>

<style>

</style>
