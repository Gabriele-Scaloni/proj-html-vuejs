<template>
  <footer>
    <div class="footer-container">
      <div class="part">
        <img src="@/assets/avadabarbers_footer_shop_image-200x156.png" alt="" />
        <button class="btn-footer"><h4>READ ABOUT OUR SERVICES</h4></button>
      </div>
      <div class="part">
        <img
          class="img-logo"
          src="@/assets/avadabarbers-logo-x2-200x70.png"
          alt="logo"
        />
        <ul>
          <li>Avada Barbers</li>
          <li>123 New York Street</li>
          <li>New York City</li>
          <li>info@yourwebsite.com</li>
          <li>11555155511223</li>
        </ul>
        <p>FOLLOW US</p>
        <ul class="ul-icons">
          <li><i class="fab fa-facebook-f"></i></li>
          <li><i class="fab fa-twitter"></i></li>
          <li><i class="fab fa-youtube"></i></li>
          <li><i class="fab fa-instagram"></i></li>
        </ul>
      </div>
      <div class="part">
        <img src="@/assets/avadabarbers_hero_focalmirror-200x275.png" alt="" />
        <button class="btn-footer"><h4>BOOK YOUR APPOINTMENT</h4></button>
      </div>
    </div>
    <div class="footer-copyright"></div>
  </footer>
</template>

<script>
export default {
  name: "MyFooter",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
footer {
  width: 100%;
  height: 400px;
  background-color: #121314;
}
.footer-container {
  width: 70%;
  margin: 0 auto;
  display: flex;
  padding: 70px 0;
}
.part {
  width: calc(100% / 3);
  margin: 0 20px;
}
img {
  width: 100%;
  height: 100px;
  object-fit: contain;
  display: block;
  margin: 0px auto 30px auto;
  text-align: center;
}
.img-logo {
  width: 100px;
  height: 100px;
}
.btn-footer {
  display: block;
  margin: 50px auto 100px auto;
  height: 40px;
  color: #be9359;
  border: 2px solid #be9359;
  background-color: transparent;
  padding: 0 10px;
}
.footer-copyright {
  width: 100%;
  height: 60px;
  background-color: #161718;
  display: flex;
}
ul {
  list-style: none;
}
li {
  color: #2b2c2c;
  text-align: center;
}
p {
  color: #be9359;
  font-size: 14px;
  text-align: center;
  margin: 15px 0;
}
.fab {
  color: white;
  margin: 5px;
}
.ul-icons {
  display: flex;
  justify-content: center;
}
</style>