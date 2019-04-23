<template>
  <div id="app">
    <TopBlock />

    <router-view />
  </div>
</template>

<script>
import TopBlock from '@/components/TopBlock';

export default {
  components: {
    TopBlock,
  }  
}
</script>

<style lang="scss">
body {
  margin: 0;
  overflow-y: scroll;
  font-family: 'Roboto', sans-serif;
}
</style>
