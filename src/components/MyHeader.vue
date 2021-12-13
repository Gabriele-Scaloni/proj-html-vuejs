<template>
  <header>
    <nav>
      <div>
        <img class="img-logo" src="@/assets/avadabarbers-logo-x2-200x70.png" alt="logo">
      </div>
      <div>
        <i class="fas fa-shopping-cart"></i>
        <i class="fas fa-bars"></i>
      </div>
    </nav>
    <div class="container-title-imgtitle">
      <div class="title-section">
        <h1>Barber Shop</h1>
        <div class="divisorio-titolo"></div>
        <p>The Pinnacle of Male Grooming</p>
        <button class="btn-header"><h4>LEARN MORE</h4> </button>
      </div>
      <div>
        <img src="@/assets/avadabarbers_hero_focalmirror-400x550.png" alt="img jumbotron">
      </div>
    </div>
    <div class="container-square">
      <div class="square">
          <div class="in-square" >
            <i class="fas fa-file-alt"></i>
            <p class="p-square">Demos</p>
          </div>
      </div>
    </div>
    <div class="container-square">
     <div class="square">
      <div class="in-square">
        <p class="price-square">$<span>39</span></p>
        <p class="p-square">On Sale</p>
      </div>
    </div>
    </div>
  </header>
</template>

<script>

export default {
  name: 'MyHeader',
  props: {
      
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
 header {
  width: 100%;
  height: 700px;
  background-color:rgb(75, 75, 75); /* da mettere bckgr img */
}
nav {
  align-items: center;
}
nav, .container-title-imgtitle{
  width: 70%;
  height: 60px;
  margin: 0 auto;
  padding-top: 10px;
  display: flex;
  justify-content: space-between;
}
.img-logo {
  width: 100px;
  height: auto;
}
.fa-shopping-cart {
  margin-right: 15px;
  color: white;
}
.fa-bars {
  color: white;
}
h1 {
  font-size: 40px;
  color: white;
}
.divisorio-titolo { 
  width: 110px;
  border: 1px solid #be9359;
}
p {
  color: #5e5d5d;
  font-size: 14px;
}
.btn-header {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 120px;
  height: 40px;
  color:#be9359 ;
  opacity: 0.4;
  border: 2px solid #be9359;
}
.title-section {
  margin-top: 150px;
}
.container-square::after {
  content: "";
  display: table;
  clear: both;
}
.square {
  width: 55px;
  height: 55px;
  background-color: white;
  border-radius: 5px;
  margin:5px 10px;
  float: right;
}
.fa-file-alt {
  position:absolute;
  left: 50%;
  top: 5px;
  transform:translate(-50%);
  font-size: 25px;
}
span {
  color:#67bd7d;
}
.in-square { 
  display: flex;
  justify-content: center;
  position: relative;
}
.p-square {
  position: absolute;
  top: 20px;
}
.price-square {
  position: absolute;
  position:absolute;
  left: 50%;
  top: 50%;
  transform:translate(-50%, -50%);
  color: #67bd7d;
  font-size: 20px;
}
</style>