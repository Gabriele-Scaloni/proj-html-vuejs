<template>
    <section class="container-section-reviews">
      <div> <!-- titolo main -->
        <p>WHAT PEOPLE SAY ABOUT US</p>   
        <h2>Reviews</h2>
      </div>
      <div class="container-reviews">
        <div class="reviews">
            <p class="description-reviews">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rem, ipsa? Molestiae consequatur alias aspernatur impedit similique enim architecto natus.</p>
          <img src="@/assets/avadabarbers-trimcut-gallery6-200x200.jpg" alt="">
          <h5>John Doe</h5>
        </div>
        <div class="reviews">
            <p class="description-reviews">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rem, ipsa? Molestiae consequatur alias aspernatur impedit similique enim architecto natus.</p>
          <img src="@/assets/avadabarbers-trimcut-gallery7-200x201.jpg" alt="">
          <h5>Pete Jones</h5>
        </div>
        <div class="reviews">
            <p class="description-reviews">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rem, ipsa? Molestiae consequatur alias aspernatur impedit similique enim architecto natus.</p>
          <img src="@/assets/avadabarbers-trimcut-gallery3-200x201.jpg" alt="">
          <h5>Mark Wilson</h5>
        </div>
      </div>
    </section>
</template>

<script>

export default {
  name: 'Reviews',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container-section-reviews {
  width: 100%;
  height: 500px;
  margin: 50px auto 0 auto;
}
.container-reviews {
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
  margin: 20px 0 30px 0;
}
.reviews {
  width:calc(100%/3) ;
  margin: 0 25px;
}
img {
  width: 100px;
  height: 100px;
  object-fit: contain;
  display:block;
  margin: 15px auto;
  border-radius: 50%;
}
h5 {
  color: #be9359;
  margin-bottom: 30px;
  text-align: center;
}
.description-reviews {
  color: #b1b1b1;
}

</style>