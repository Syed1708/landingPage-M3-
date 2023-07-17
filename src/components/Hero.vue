<script setup>
//import { heroData } from '../data/heroData';

const heroData = [
    {
        title: "HERO TITLE",
        description: `Lorem ipsum dolor, sit amet consectetur adipisicing elit. Numquam ipsam eaque modi, iste est atque
        voluptates officia? Ipsam, corporis!
        Eius consequuntur nostrum necessitatibus nam assumenda consequatur quas iste rerum autem.`,
        btnText: "About Us",
        btnLink: ""
    },


]


</script>

<template>
    
<!-- ======= Hero Section ======= -->
<section id="hero" class="d-flex align-items-center">
  <div class="container d-flex flex-column align-items-center" data-aos="zoom-in" data-aos-delay="100">
    <h1>{{ heroData[0].title }}</h1>
    <h2>{{ heroData[0].description }}</h2>
    <a :href="heroData[0].btnLink" class="btn-about">{{ heroData[0].btnText }}</a>
  </div>
</section><!-- End Hero -->

</template>


<style scoped>
#hero {
  width: 100%;
  height: 100vh;
  background: url("../assets/images/slide3.jpg") top right;
  background-size: cover;
}

#hero .container {
  padding-top: 70px;
  position: relative;
}

</style>