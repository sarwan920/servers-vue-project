<template>
  <div class="container">
    <app-header></app-header>
    <hr>
    <div class="row justify-content-center">
      <app-servers></app-servers>
      <app-servers-details></app-servers-details>
    </div>
  <hr>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from "./components/Shared/Header.vue";
import Footer from "./components/Shared/Footer.vue";
import Servers from "./components/Server/Servers.vue";
import ServersDetails from "./components/Server/ServersDetails.vue";
export default {
  components: {
    "app-header": Header,
    "app-servers": Servers,
    "app-servers-details": ServersDetails,
    "app-footer": Footer
  }
};
</script>

<style>
/* div{
 color:#398fb1;
} */
</style>
