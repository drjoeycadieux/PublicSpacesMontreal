<script setup>
import Navbar from "../components/Navbar.vue";
import Alerts from "../components/Alerts.vue";
</script>

<template>
  <div>
    <Alerts />
    <Navbar />
    <div id="header-begin-top-background" class="header-begin-top">
      <h1>Welcome To PublicSpaces | Montreal</h1>
    </div>
  </div>
</template>

<style scoped>
.header-begin-top {
  text-align: center;
  font-family: sans-serif;
  padding: 160px;
  font-weight: bold;
}

.header-begin-top h1 {
  color: white;
  font-size: 30px;
}

#header-begin-top-background {
  background-image: url(../assets/day54-building.png);
  background-size: contain;
}
</style>
