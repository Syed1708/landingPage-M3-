<script setup>
const headerData = [
    {
        title: "LANDING PAGE",
    }

    
]

const navList = [
    {
        title: "Home",
        path : '#'
    },
    {
        title: "Assignments",
        path : '#assignments'
    },
    {
        title: "Pricing",
        path : '#pricing'
    },
    {
        title: "Testimonials",
        path : '#testimonials'
    },
    {
        title: "Contact Us",
        path : '#contact_us'
    },

    
]


</script>

<template>
    
<!-- ======= Header ======= -->
<header id="header" class="fixed-top">
    <div class="container-fluid d-flex justify-content-between align-items-center">

      <h1 class="logo me-auto me-lg-0"><a href="">{{ headerData[0].title }}</a></h1>


      <nav id="navbar" class="navbar order-last order-lg-0">
        <ul>
          <li class="nav-item"><a class="nav-link" href="#">{{ navList[0].title }}</a></li>
          <li class="nav-item"><a class="nav-link" :href="navList[1].path">{{ navList[1].title }}</a></li>
          <li class="nav-item"><a class="nav-link" :href="navList[2].path">{{ navList[2].title }}</a></li>
          <li class="nav-item"><a class="nav-link" :href="navList[3].path">{{ navList[3].title }}</a></li>
          <li class="nav-item"><a class="nav-link" :href="navList[4].path">{{ navList[4].title }}</a></li>
        </ul>
        <i class="fa-solid  fa-list bi bi-list mobile-nav-toggle"></i>
        
      </nav><!-- .navbar -->

      <div class="header-social-links">
        <a href="#" class="twitter"><i class="fa-brands fa-twitter"></i></a>
        <a href="#" class="facebook"><i class="fa-brands fa-facebook"></i></a>
        <a href="#" class="instagram"><i class="fa-brands fa-instagram"></i></a>
        <a href="#" class="linkedin"><i class="fa-brands fa-linkedin"></i></a>
      </div>

    </div>

  </header><!-- End Header -->


</template>
