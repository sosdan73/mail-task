<template>
  <div id="app">
    <app-header />
    <app-content />
    <app-footer />
  </div>
</template>

<script>
import appHeader from './components/Header.vue';
import appFooter from './components/Footer.vue';
import appContent from './components/content/Content.vue';

export default {
  name: 'App',
  components: {
    appHeader,
    appFooter,
    appContent
  }
}
</script>

<style lang="scss">
  body {
    margin: 0;
  }
</style>
