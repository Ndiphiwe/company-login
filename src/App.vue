<template>
  <div id="app">
    <Navbar />
      <router-view />
  </div>
</template>
<script>
import Navbar from '@/components/Navbar.vue'
export default {
  components: {Navbar}
};
</script>
<style>
body{
  background: url("https://i.postimg.cc/fbd1nXWj/s-h-bg.jpg");
  background-size: cover;
  /* background-position: center; */
  background-repeat: no-repeat;
}
</style>
