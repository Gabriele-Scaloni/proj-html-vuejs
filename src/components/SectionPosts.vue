<template>
  <section class="container-section-services">
    <svg
      class="fusion-big-triangle-candy"
      xmlns="http://www.w3.org/2000/svg"
      version="1.1"
      width="100%"
      height="100"
      viewBox="0 0 100 100"
      preserveAspectRatio="none"
      style="fill: #ffffff; padding: 0"
    >
      <path d="M0 100 L50 2 L100 100 Z"></path>
    </svg>
    <div class="container-title-blog">
      <!-- titolo main -->
      <p>TALES FROM THE BARBER SHOP</p>
      <h2>Recent Blog Posts</h2>
    </div>
    <div class="container-service">
      <div class="service">
        <img src="@/assets/avadabarbers-choosing-blog-320x202.jpg" alt="" />
        <h3>Avada Barber Now Open</h3>
        <p class="description-services">
          Avada Barbers are axperts in the lickety split and hair cut. Quick but
          careful and ridiculously good looking.
        </p>
      </div>
      <div class="service">
        <img src="@/assets/avadabarbers-choosing-blog-700x441.jpg" alt="" />
        <h3>Choosing The Right Barber</h3>
        <p class="description-services">
          Take a seat in our fine leather chairs, lean back and let us lather
          you a fresh head in a luxurious fashioin.
        </p>
      </div>
      <div class="service">
        <img src="@/assets/avadabarbers-ourservice-blog-700x441.jpg" alt="" />
        <h3>Quick Service Guide</h3>
        <p class="description-services">
          Tame the tangles and untidy facial hairs like a gentleman with our
          Beard Tidy services from Avada Barbers.
        </p>
      </div>
    </div>
    <button class="btn-services"><h4>READ ABOUT FROM OUR BLOG</h4></button>
  </section>
</template>

<script>
export default {
  name: "SectionPosts",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container-section-services {
  width: 100%;
  height: 850px;
  margin: 0 auto;
  background-color: #f5f5f5;
}
.fusion-big-triangle-candy {
  transform: rotate(180deg);
  -ms-transform: rotate(180deg); /* IE 9 */
  -webkit-transform: rotate(180deg); /* Safari e Chrome */
}
.container-title-blog {
  margin-top: 50px;
}
.container-service {
  width: 60%;
  margin: 0 auto;
  display: flex;
  justify-content: center;
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
  margin: 20px 0 50px 0;
}
.service {
  width: calc(100% / 3);
  margin: 0 20px;
}
img {
  width: 220px;
  height: 220px;
  object-fit: contain;
  display: block;
  margin: 0px auto 15px auto;
  text-align: center;
}
h3 {
  color: #be9359;
  margin-bottom: 30px;
  text-align: center;
}
.description-services {
  color: #b1b1b1;
}
.btn-services {
  display: block;
  margin: 50px auto 100px auto;
  height: 40px;
  color: #be9359;
  border: 2px solid #be9359;
  background-color: transparent;
  padding: 0 15px;
}
</style>