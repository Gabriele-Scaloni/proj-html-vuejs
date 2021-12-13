<template>
  <div class="container-main">
    <div class="contenitore">
      <p>AWARD WINNIG</p>   
      <h2>Pro Barbers</h2>
      <button class="btn-main"> MEET YOUR NEW BARBER</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyMain',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container-main {
  width: 100%;
  height: 400px;
  background-image:url("~@/assets/avadabarbers-about-introbackground.jpg");
  display: flex;
  justify-content: center;
}
.contenitore {
  margin-top: 100px;
}
p {
  color: #be9359;
}
h2 {
  color: #b1b1b1;
}
.btn-main {
  widows: 120px;
  height: 40px;
  opacity: 0.3;
  color: #be9359;
  border: 1px solid #be9359;
}
</style>