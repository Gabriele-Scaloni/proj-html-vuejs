<template>
  <section class="container-section-services">
    <div> <!-- titolo main -->
      <p>MENS GROOMING</p>   
      <h2>Services</h2>
    </div>
    <div class="container-service">
      <Services v-for="service, j in services"
      :img="service.image"
      :nomeservizio="service.name"
      :descrizioneservizio="service.description"
      :key="j"/>
    </div>
    <button class="btn-services"><h4>READ ABOUT OUR SERVICES</h4> </button>
  </section>
</template>

<script>
import Services from './Services.vue'

export default {
  name: "SectionServices",
    components: {
    Services,
  },
 data(){
    return {
      services: [
        {
          image:"avadabarbers-trimcut-icon-before.png",
          name:"Trim & cut",
          description:"Avada Barbers are axperts in the lickety split and hair cut. Quick but careful and ridiculously good looking.",
        },
        {
          image:"avadabarbers-washndry-icon.png",
          name:"Wash & Dry",
          description:"Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a luxurious fashioin.",
        },
        {
          image:"avadabarbers-beardtrim-icon.png",
          name:"Beard Tidy",
          description:"Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.",
        }
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container-section-services {
  width: 100%;
  height: 700px;
  margin: 100px auto;
}
.container-service {
  width: 60%;
  margin: 0 auto;
  display: flex;
  justify-content: space-around;
}
h2 {
  color: #b1b1b1;
  text-align: center;
  font-size: 40px;
  margin: 20px 0 100px 0;
}
p {
  color: #be9359;
  text-align: center;
  font-size: 14px;
}
.btn-services {
  display: block;
  margin: 50px auto 100px auto;
  height: 40px;
  color:#be9359 ;
  border: 2px solid #be9359;
  background-color: transparent;
  padding: 0 15px;
}

</style>