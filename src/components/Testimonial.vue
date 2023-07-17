<script setup>
const testimonialData = [
    {
        title: "Testimonials",
        des: "Here  I will add my all assignments one by one with Vue JS"
    },
    {
        image:'https://mdbcdn.b-cdn.net/img/Photos/Avatars/img%20(10).webp',
        name: 'Maria Kate',
        designation: 'Photographer',
        description: `Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus et deleniti
        nesciunt sint eligendi reprehenderit reiciendis, quibusdam illo, beatae quia fugit
        consequatur laudantium velit magnam error. Consectetur distinctio fugit
        doloremque.`
    },
    {
        image:'https://mdbcdn.b-cdn.net/img/Photos/Avatars/img%20(32).webp',
        name: 'Jane Doe',
        designation: 'Web Developer',
        description: `Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus et deleniti
        nesciunt sint eligendi reprehenderit reiciendis, quibusdam illo, beatae quia fugit
        consequatur laudantium velit magnam error. Consectetur distinctio fugit
        doloremque.`
    },
    {
        image:'https://mdbcdn.b-cdn.net/img/Photos/Avatars/img%20(1).webp',
        name: 'Anna Deynah',
        designation: 'UX Designer',
        description: `Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus et deleniti
        nesciunt sint eligendi reprehenderit reiciendis, quibusdam illo, beatae quia fugit
        consequatur laudantium velit magnam error. Consectetur distinctio fugit
        doloremque.`
    },
    
]
</script>

<template>
        <!-- ======= Testimonial Section ======= -->
        <section id="testimonials" class="testimonials">
      <div class="container" data-aos="fade-up">

        <div class="section-title">
          <h2>{{ testimonialData[0].title }}</h2>
          <p>{{ testimonialData[0].des }}</p>
        </div>

        <!-- Carousel wrapper -->
        

    <div id="carouselExampleDark" class="carousel carousel-dark slide">
 
      <div class="carousel-inner">         
      
        <div class="carousel-item active">
          <img class="rounded-circle shadow-1-strong mb-4" :src="testimonialData[1].image" :alt="testimonialData[1].name" style="width: 150px;">
          <div class="row d-flex justify-content-center">
            <div class="col-lg-8">
              <h5 class="mb-3">{{ testimonialData[1].name }}</h5>
              <p>{{ testimonialData[1].designation }}</p>
              <p class="text-muted">
                <i class="fas fa-quote-left pe-2"></i>
                {{ testimonialData[1].description }}
              </p>
            </div>
          </div>
          <ul class="list-unstyled d-flex justify-content-center text-warning mb-0">
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="far fa-star fa-sm"></i></li>
          </ul>
        </div>
        <div class="carousel-item">
          <img class="rounded-circle shadow-1-strong mb-4" :src="testimonialData[2].image" :alt="testimonialData[2].name" style="width: 150px;">
          <div class="row d-flex justify-content-center">
            <div class="col-lg-8">
              <h5 class="mb-3">{{ testimonialData[2].name }}</h5>
              <p>{{ testimonialData[2].designation }}</p>
              <p class="text-muted">
                <i class="fas fa-quote-left pe-2"></i>
                {{ testimonialData[2].description }}
              </p>
            </div>
          </div>
          <ul class="list-unstyled d-flex justify-content-center text-warning mb-0">
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="far fa-star fa-sm"></i></li>
          </ul>
        </div>
        <div class="carousel-item">
          <img class="rounded-circle shadow-1-strong mb-4" :src="testimonialData[3].image" :alt="testimonialData[3].name" style="width: 150px;">
          <div class="row d-flex justify-content-center">
            <div class="col-lg-8">
              <h5 class="mb-3">{{ testimonialData[3].name }}</h5>
              <p>{{ testimonialData[3].designation }}</p>
              <p class="text-muted">
                <i class="fas fa-quote-left pe-2"></i>
                {{ testimonialData[3].description }}
              </p>
            </div>
          </div>
          <ul class="list-unstyled d-flex justify-content-center text-warning mb-0">
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="fas fa-star fa-sm"></i></li>
            <li><i class="far fa-star fa-sm"></i></li>
          </ul>
        </div>

      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>


    </div>

    </section>

    <!-- ======= End testimonials Section ======= -->
</template>