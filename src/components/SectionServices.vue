<template>
  
    <section class="container-section-services">
      <div> <!-- titolo main -->
        <p>MENS GROOMING</p>   
        <h2>Services</h2>
      </div>
      <div class="container-service">
        <div class="service">
          <img src="@/assets/avadabarbers-trimcut-icon-before.png" alt="">
          <h3>Trim & cut </h3>
          <p class="description-services">Avada Barbers are axperts in the lickety split and hair cut. Quick but careful and ridiculously good looking.</p>
        </div>
        <div class="service">
          <img src="@/assets/avadabarbers-washndry-icon.png" alt="">
          <h3>Trim & cut </h3>
          <p class="description-services">Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a luxurious fashioin.</p>
        </div>
        <div class="service">
          <img src="@/assets/avadabarbers-beardtrim-icon.png" alt="">
          <h3>Trim & cut </h3>
          <p class="description-services">Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.</p>
        </div>
      </div>
      <button class="btn-services"><h4>READ ABOUT OUR SERVICES</h4> </button>
    </section>
</template>

<script>

export default {
  name: 'SectionServices',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container-section-services {
  width: 60%;
  height: 500px;
  margin: 100px auto;
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
  margin: 20px 0 100px 0;
}
.container-service {
  display: flex;
}
.service {
  width:calc(100%/3) ;
  margin: 0 20px;
  }
img {
  width: 75px;
  height: 100px;
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
  display:block;
  margin:50px auto;
  height: 40px;
  color:#be9359 ;
  border: 2px solid #be9359;
  background-color: white;
  padding: 0 15px;
}
</style>