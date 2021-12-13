<template>
  <header>
    <nav>
      <div>
        <img class="img-logo" src="@/assets/avadabarbers-logo-x2-200x70.png" alt="logo">
      </div>
      <div>
        <i class="fas fa-bars"></i>
        <i class="fas fa-shopping-cart"></i>
      </div>
    </nav>
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
  height: 400px;
  background-color:grey; 
}
nav {
  width: 70%;
  height: 50px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center ;
}
.img-logo {
  width: 100px;
  height: auto;
}
.fas {
  color: white;
  margin-left: 7px;
}
</style>