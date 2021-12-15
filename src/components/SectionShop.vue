<template>
  <section class="container-section-shop">
    <svg
      class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill: #121314; padding: 0">
      <path d="M0 100 L50 2 L100 100 Z"></path>
    </svg>
    <div>
      <p>WE HAVE YOU COVERED</p>
      <h2>Avada Grooming Products</h2>
    </div>
    <div class="container-products">
      <Products v-for="prodotto, i in prodotti"
        :img="prodotto.image"
        :descrizione="prodotto.description"
        :prezzo="prodotto.price"
        :key="i" 
      />
    </div>
    <div>
      <button class="btn-shop">SHOP OUR PRODUCT RANGE</button>
    </div>
  </section>
</template>

<script>
import Products from './Products.vue'

export default {
  name: "SectionShop",
    components: {
    Products,
  },
  data(){
    return {
      prodotti: [
        {
          image:"brush_dark-400x400.png",
          description:"Brush",
          price:"$15.00",
        },
        {
          image:"scissors-400x400.png",
          description:"Scissors",
          price:"$85.00",
        },
        {
          image:"hot_oil_dark-400x400.png",
          description:"Hot Oil",
          price:"$15.00",
        },
        {
          image:"straight_razor_dark-400x400.png",
          description:"Straight Razor",
          price:"$30.00",
        }
      ]
    }
  }
};
</script>
<style scoped lang="scss">
.container-section-shop {
  width: 100%;
  height: 600px;
  background-image: url("~@/assets/avadabarbers-reviewsbackground.jpg");
  background-size: cover;
  position: relative;
}
.fusion-big-triangle-candy {
  width: 100%;
  color: black;
  position: absolute;
  top: -100px;
}
p {
  color: #be9359;
  text-align: center;
  font-size: 14px;
}
h2 {
  color: #b1b1b1;
  text-align: center;
  font-size: 40px;
  margin: 10px 0 50px 0;
}
.container-products {
  width: 90%;
  margin: 0 auto;
  display: flex;
  justify-content: space-around;
}
.btn-shop {
  height: 40px;
  color: #be9359;
  border: 1px solid #be9359;
  background-color: transparent;
  padding: 0 15px;
  display: block;
  margin: 40px auto;
}
</style>