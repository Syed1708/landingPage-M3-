<script setup>

import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Assaignment from './components/Assignment.vue'
import Pricing from './components/Pricing.vue'
import Testimonial from './components/Testimonial.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

// Remember one this if there is an error mabybe problem with div  

</script>

<template>

  <!-- wrapping with div is very important -->

<div data-bs-spy="scroll" data-bs-target="#navbar" data-bs-smooth-scroll="true">
  
<Header/>
<Hero/>
<Assaignment/>
<Pricing/>
<Testimonial/>
<Contact/>
<Footer/>

</div>

</template>

<style scoped>

</style>
