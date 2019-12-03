<template>
  <div id="app">
    <TopBar />
    <Slider />
    <MainPanelTop />
    <MainPanel />
  </div>
</template>

<script>
import TopBar from './components/TopBar.vue';
import Slider from './components/Slider.vue';
import MainPanelTop from './components/MainPanelTop.vue';
import MainPanel from './components/MainPanel.vue';

export default {
  name: 'app',
  components: {
    TopBar,
    Slider,
    MainPanelTop,
    MainPanel
  }
}
</script>

<style lang="scss">
@import './assets/styles/style.css';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
