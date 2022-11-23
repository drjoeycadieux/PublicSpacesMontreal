<script setup></script>

<template>
  <div class="navbar-top-menu">
    <ul>
      <li>
        <h3>Public Spaces | Montreal</h3>
      </li>
      <li>
        <router-link class="link-nav" to="#">Home</router-link>
      </li>
      <li>
        <router-link class="link-nav" to="#">Discover</router-link>
      </li>
      <li>
        <router-link class="link-nav" to="#">Information</router-link>
      </li>
      <li>
        <router-link class="link-nav" to="#">About</router-link>
      </li>
    </ul>
  </div>
</template>

<style scoped>
.navbar-top-menu {
  padding: 25px;
  background-color: rgb(33, 40, 59);
}
.navbar-top-menu ul {
  display: block;
}
.navbar-top-menu ul li {
  display: inline;
  margin: 10px;
}
.link-nav {
  text-decoration: none;
  color: white;
  font-family: sans-serif;
  font-weight: bold;
}

.link-nav:hover {
  color: lightslategray;
}

.navbar-top-menu h3 {
  display: inline;
  font-family: sans-serif;
  font-weight: bold;
  font-size: 25px;
  color: white;
}
</style>
