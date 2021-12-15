<template>
  <ul>
      <li class="service">
          <img :src="require(`@/assets/${img}`)" alt="">
          <h3>{{nomeservizio}}</h3>
          <p class="description-services">{{descrizioneservizio}}</p> 
      </li>
  </ul>
</template>

<script>
export default {
  name: "Services",
  props: {
    img:String,
    nomeservizio:String,
    descrizioneservizio:String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
ul {
    list-style-type: none;
}

h3 {
  color: #be9359;
  text-align: center;
  margin: 25px 0 10px 0;
}
img {
  width: 200px;
  height: 100px;
  object-fit: contain;
  display:block;
  margin:0px auto 30px auto;
}
p {
  color: #be9359;
  text-align: center;
  font-size: 14px;
}

h3 {
  color: #be9359;
  margin-bottom: 30px;
  text-align: center;
}
.description-services {
  color: #b1b1b1;
}
</style>