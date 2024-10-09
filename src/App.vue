<template>
  <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
  <br>
  <router-link to="/">Home</router-link> |
  <router-link to="/about">About</router-link> |
  <a href="/about">A tag About</a> <!-- the <a> link by clicking, refresh the page = not good for UX-->
  <router-view></router-view>
</template>

<script setup>

</script>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
