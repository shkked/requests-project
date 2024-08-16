<template>
  <div id="app">
    <v-container>
      <headerPage />
    </v-container>
  </div>
</template>

<script>
import headerPage from './components/headerPage.vue'
export default {
  name: 'App',
  components: {
    headerPage
  }
}
</script>


<style lang="scss">
@import './assets/_main.scss';

#app{
  background: rgba(238, 238, 238, 1);
  gap: 20px;
  height: 100%;
}
</style>
