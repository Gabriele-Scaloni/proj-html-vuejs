<template>
  <section class="section-productmonth">
    <div class="contenitore-productmonth">
      <div class="container-img">
        <img src="@/assets/shaving_butter-800x800.png" alt="" />
      </div>
      <div class="buy-now">
        <p><strong>THIS MONTHS FEATURED PRODUCT</strong></p>
        <h2>Shaving Butter</h2>
        <p class="lorem">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus id
          sint obcaecati, tempore nostrum totam repellendus tempora, earum
          voluptates amet autem, nam consequatur voluptas eaque ab? Architecto
          porro autem explicabo?
        </p>
        <button class="btn-buy">BUY NOW</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ProductMonth",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.section-productmonth {
  width: 100%;
  height: 300px;
  position: relative;
}
.contenitore-productmonth {
  width: 70%;
  height: 300px;
  margin: 0 auto;
  background-color: #121413;
  position: absolute;
  top: -30px;
  left: 50%;
  transform: translate(-50%);
  border-top: 2px solid #be9359;
  display: flex;
}
.container-img {
  width: 40%;
  background-image: url("~@/assets/avadabarbers-cta-background.jpg");
  background-size: cover;
  position: relative;
  img {
    width: 250px;
    height: 250px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
}
.buy-now {
  width: 60%;
  height: auto;
  padding: 30px;
}
p {
  color: #be9359;
  font-size: 14px;
}
h2 {
  color: #b1b1b1;
  font-size: 40px;
  margin: 10px 0 25px 0;
}
.lorem {
  color: #686868;
}
.btn-buy {
  height: 40px;
  color: #be9359;
  border: 1px solid #be9359;
  background-color: transparent;
  margin-top: 20px;
  padding: 0 30px;
}
</style>