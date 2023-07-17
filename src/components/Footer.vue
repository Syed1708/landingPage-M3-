<script setup>
const footerData = [
    {
        design_by: "Designed by",
        design_name: "SNA",
    }

    
]
</script>
    

<template>
    

<div> <!-- without wraping this div this will show an error -->

<!-- ======= Footer ======= -->
<footer id="footer">
  <div class="container">
    <div class="copyright">
      &copy; Copyright <strong><span>SYED</span></strong>. All Rights Reserved
    </div>
    <div class="credits">
      {{ footerData[0].design_by }} <a href="#">{{ footerData[0].design_name }}</a>
    </div>
  </div>
</footer><!-- End  Footer -->

<!-- preloader -->
<div id="preloader"></div>


<!-- up and down -->
<a href="#" class="back-to-top d-flex align-items-center justify-content-center">
  <i class="fa-solid fa-arrows-up-down"></i>
  </a>

</div>


</template>