<template>
  <div id="app">
    <router-view class="view"></router-view>
    <!-- <router-link class="view" name="subject"></router-link> -->
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
#app {
  max-width: 41.2rem;
  margin: 0 auto;
}
html{
  font-size: 62.5%;
}
* {
  margin: 0;
  padding: 0;
}

li{
  list-style: none;
}

a{
  text-decoration: none;
}
</style>
