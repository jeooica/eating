<template>
  <!-- <home-page></home-page> -->
  <random-page></random-page>
</template>

<script>
import HomePage from './views/HomePage.vue'
import RandomPage from './views/RandomRestaurant.vue'
export default {
  name: 'App',
  components: {HomePage, RandomPage}
}
</script>
<style>

</style>
