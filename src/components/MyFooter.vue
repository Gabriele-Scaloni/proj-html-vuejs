<template>
  
    <section class="container-footer">
      <div> <!-- titolo main -->
        <img class="img-logo-footer" src="@/assets/avadabarbers-logo-x2-200x70.png" alt="">
      </div>
      <div class="container-service">
        <div class="service">
          <img src="@/assets/avadabarbers-choosing-blog-320x202.jpg" alt="">
          <h3>Avada Barber Now Open </h3>
          <p class="description-services">Avada Barbers are axperts in the lickety split and hair cut. Quick but careful and ridiculously good looking.</p>
        </div>
        <div class="service">
          <img src="@/assets/avadabarbers-choosing-blog-700x441.jpg" alt="">
          <h3>Choosing The Right Barber</h3>
          <p class="description-services">Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a luxurious fashioin.</p>
        </div>
        <div class="service">
          <img src="@/assets/avadabarbers-ourservice-blog-700x441.jpg" alt="">
          <h3>Quick Service Guide</h3>
          <p class="description-services">Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.</p>
        </div>
      </div>
      <button class="btn-services"><h4>READ ABOUT OUR BLOG</h4> </button>
    </section>
</template>

<script>

export default {
  name: 'MyFooter',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container-footer {
  width: 100%;
  height: 700px;
  margin: 0 auto;
  background-color: #121314;
}
.fusion-big-triangle-candy {
    transform:rotate(180deg);
    -ms-transform: rotate(180deg); /* IE 9 */
    -webkit-transform: rotate(180deg); /* Safari e Chrome */
}
.container-title-blog {
  margin-top: 50px;
}
.container-service {
  width: 60%;
  margin:0 auto;
  display: flex;
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
  width:calc(100%/3) ;
  margin: 0 20px;
  }
.img-logo-footer {
  width: 100px;
  height: 100px;
  object-fit: contain;
  display:block;
  margin:0px auto 30px auto;
  text-align:center;
}
img {
  width: 200px;
  height: 200px;
  object-fit: contain;
  display:block;
  margin:0px auto 30px auto;
  text-align:center;
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
  color:#be9359 ;
  border: 2px solid #be9359;
  background-color: white;
  padding: 0 15px;
}

</style>