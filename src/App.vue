<template>
  <div id="app">
    <HeaderVue/>
    <main-vue/>
    <merch-vue/>
    <info-vue/>
    <footer-vue/>
  </div>
</template>

<script>
import HeaderVue from './components/HeaderComponent.vue'
import MainVue from './components/MainComponent.vue'
import MerchVue from './components/MerchComponent.vue'
import InfoVue from './components/InfoComponent.vue'
import FooterVue from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderVue,
    MainVue,
    MerchVue,
    InfoVue,
    FooterVue
  }
}
</script>

<style lang="scss">
*{
  margin: 0 auto;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
