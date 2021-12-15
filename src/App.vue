<template>
  <div id="app">

    <MyHeader/>

    <MyMain/>

    <SectionServices/>

    <SectionShop/>

    <ProductMonth/>

    <Reviews/>

    <SectionPosts/>

    <MyFooter/>

  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import SectionServices from './components/SectionServices.vue'
import SectionShop from './components/SectionShop.vue'
import ProductMonth from './components/ProductMonth.vue'
import Reviews from './components/Reviews.vue'
import SectionPosts from './components/SectionPosts.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    SectionServices,
    SectionShop,
    ProductMonth,
    Reviews,
    SectionPosts,
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
