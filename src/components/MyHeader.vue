<template>
    <header>
      <nav>
        <div>
          <img class="img-logo" src="@/assets/avadabarbers-logo-x2-200x70.png" alt="logo">
        </div>

        <div>

        </div>
      </nav>
    </header>
</template>

<script>

import '@fortawesome/fontawesome-svg-core'
import '@fortawesome/free-solid-svg-icons'
import '@fortawesome/vue-fontawesome'

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
</style>