<script>
  import Navbar from './components/Navbar.vue';
  export default {
    components: { Navbar },
  };
</script>

<template>
  <Navbar />
  <div class="content">
    <RouterView />
  </div>
</template>

<style lang="scss" scoped>
  .content {
    margin: 0 auto;
    max-width: 1200px;
    padding: 0 20px;
  }
</style>
