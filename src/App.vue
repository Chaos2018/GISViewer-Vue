<template>
  <div id="app">
    <home></home>
    <router-view />
  </div>
</template>

<script lang="ts">
import {Component, Vue} from 'vue-property-decorator';
import Home from '@/components/Home.vue';

@Component({
  components: {
    Home
  }
})
export default class App extends Vue {}
</script>

<style>
body {
  padding: 0;
  margin: 0;
  height: 100%;
  width: 100%;
}

#app {
  height: 100vh;
}
</style>
