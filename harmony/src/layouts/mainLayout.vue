<template>
  <div class="container-fluid p-0">
    <!-- <div class="row"> -->
      <Header />
      <div class="row">
        <router-view />
      </div>
    <!-- </div> -->
  </div>
</template>

<script setup>
import Header from '@/components/common/header.vue'
</script>
<style scoped>
body {
  font-family: "Open Sans", sans-serif;
  color: #444444 !important;
}

a {
  color: #ff4a17;
  text-decoration: none;
}

a:hover {
  color: #ff724a;
  text-decoration: none;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Raleway", sans-serif;
}
</style>