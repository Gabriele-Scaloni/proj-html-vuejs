<template>
    <section class="container-section-shop">
        <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100"  preserveAspectRatio="none" style="fill:#121314;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg>
        <div> <!-- titolo main -->
            <p>WE HAVE YOU COVERED</p>   
            <h2>Avada Grooming Products</h2>
        </div>
        <div>
            <ul class="ul-shop">
                <li>
                    <img src="@/assets/brush_dark-400x400.png" alt="">
                    <h3>Brush</h3>
                    <p>$15.00</p>
                </li>
                <li>
                    <img src="@/assets/scissors-400x400.png" alt="">
                    <h3>Scissors</h3>
                    <p>$85.00</p>
                </li>
                <li>
                    <img src="@/assets/hot_oil_dark-400x400.png" alt="">
                    <h3>Hot Oil</h3>
                    <p>$15.00</p>
                </li>
                <li>
                    <img src="@/assets/straight_razor_dark-400x400.png" alt="">
                    <h3>Straight Razor</h3>
                    <p>$30.00</p>
                </li>
            </ul>
            <button class="btn-shop"> SHOP OUR PRODUCT RANGE </button>
        </div>
    </section>
</template>

<script>

export default {
  name: 'SectionShop',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.container-section-shop {
  width: 100%;
  height: 600px;
  background-image: url('~@/assets/avadabarbers-reviewsbackground.jpg');
  background-size:contain;

  position: relative;
}
.fusion-big-triangle-candy {
  width: 100%;
  color: black;
  position:absolute;
  top:-100px;
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
h3 {
    color: #be9359;
    text-align: center;
    margin:40px 0 20px 0;
}
.ul-shop {
    width: 90%;
    margin: 0 auto;
    display: flex;
    justify-content: space-around;
    list-style: none;
}
img {
    width: 200px;
    object-fit: contain;
}
.btn-shop {
  height: 40px;
  color: #be9359;
  border: 1px solid #be9359;
  background-color: transparent;
  padding: 0 15px;
  display:block;
  margin: 40px auto;
}
</style>