<template>
  <div id="app">

    <MyHeader/>

    <MyMain/>

    <SectionServices/>

    <SectionShop/>

    <MyFooter/>

  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import SectionServices from './components/SectionServices.vue'
import SectionShop from './components/SectionShop.vue'
import MyFooter from './components/MyFooter.vue'


export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    SectionServices,
    SectionShop,
    MyFooter
  }
}
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
