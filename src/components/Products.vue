<template>
    <div>
        <ul>
            <li>
                <img :src="require(`@/assets/${img}`)" alt="">
                <h3>{{descrizione}}</h3>
                <p>{{prezzo}}</p> 
            </li>
        </ul>
  </div>
</template>

<script>
export default {
  name: "Products",
  props: {
    img:String,
    descrizione:String,
    prezzo:String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  color: #be9359;
  text-align: center;
  margin: 25px 0 10px 0;
}
img {
  width: 200px;
  object-fit: contain;
}
p {
  color: #be9359;
  text-align: center;
  font-size: 14px;
}
ul {
list-style-type: none;
}
</style>