<script setup>
import Navbar from "../components/Navbar.vue";
import Alerts from "../components/Alerts.vue";
</script>

<template>
  <div>
    <Alerts />
    <Navbar />
    <div class="header-begin-top">
      <h1>Welcome To PublicSpaces | Montreal</h1>
    </div>
  </div>
</template>

<style scoped>
.header-begin-top {
  text-align: center;
  font-family: sans-serif;
  padding: 15px;
  font-weight: bold;
}
</style>
