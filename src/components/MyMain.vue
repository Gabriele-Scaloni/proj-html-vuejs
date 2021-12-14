<template>
  <div class="container-main">
    <div class="contenitore">
      <p>AWARD WINNIG</p>   
      <h2>Pro Barbers</h2>
      <button class="btn-main"> MEET YOUR NEW BARBER </button>
    </div>
    <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100"  preserveAspectRatio="none" style="fill:#ffffff;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg>
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
  height: 500px;
  background-image:url("~@/assets/avadabarbers-about-introbackground.jpg");
  display: flex;
  justify-content: center;
  position: relative;
}
.contenitore {
  margin-top: 100px;
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
  margin: 20px 0;
}
.btn-main {
  widows: 120px;
  height: 40px;
  opacity: 0.3;
  color: #be9359;
  border: 1px solid #be9359;
  padding: 0 15px;
  position: absolute;
  left: 50%;
  transform: translate(-50%);
}
.fusion-big-triangle-candy {
  position: absolute;
  bottom: 0;
}
</style>