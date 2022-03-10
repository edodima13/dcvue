<template>
  <div id="app">
    <HeaderVue/>
    <main-vue/>
    <merch-vue/>
  </div>
</template>

<script>
import HeaderVue from './components/HeaderComponent.vue'
import MainVue from './components/MainComponent.vue'
import MerchVue from './components/MerchComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderVue,
    MainVue,
    MerchVue
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
