<template>
  <div id="app">
      <Header />
  </div>
</template>

<script>
  import Header from '@/Header.vue';

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang='scss'>
  @import url('https://use.fontawesome.com/releases/v5.7.2/css/all.css');

  body {
    margin: 0;
    padding: 0;
    background-color: gray;
  }
</style>
