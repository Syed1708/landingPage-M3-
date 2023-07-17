<script setup>

const contactData = [
    {
        title: "Contact Us",
        description: "Here you can contact us if you have any qustion."
    },

]


const adressData = [
    {
        addL1: "1 AVENUE DE LAROQUE",
        addL2: "33300, BORDEAUX, FRANCE",
        phone1: '+33867785858',
        phone2: '+33867755737'
    },
    
]

</script>


<template>
    
    <!-- ======= Contact Section ======= -->


    <section id="contact_us" class="contact_us">
      <div class="container" data-aos="fade-up">

        <div class="section-title">
          <h2>{{ contactData[0].title }}</h2>
          <p>{{ contactData[0].description }}</p>
        </div>

        <div class="row">
          <div class="col-lg-7">
            <form class="contact-form">
              <div class="row">
                <div class="col-6">
                  <div class="form-group">
                    <label class="" for="fname">First name</label>
                    <input type="text" class="form-control" id="fname">
                  </div>
                </div>
                <div class="col-6">
                  <div class="form-group">
                    <label class="" for="lname">Last name</label>
                    <input type="text" class="form-control" id="lname">
                  </div>
                </div>
              </div>
              <div class="form-group">
                <label class="" for="email">Email address</label>
                <input type="email" class="form-control" id="email">
              </div>
              <div class="form-group">
                <label class="" for="message">Message</label>
                <textarea name="" class="form-control" id="message" cols="30" rows="5"></textarea>
              </div>

              <button type="submit" class="btn btn-primary mt-3">Send Message</button>
            </form>
          </div>
          
          <div class="col-lg-4 ml-auto p-3" data-aos="fade-up" data-aos-delay="200">
            
            <h3 class="h5 mb-4">Contact Info</h3>

            <address class="text-black">
              <i class="fa fa-location"></i>
              <span>{{ adressData[0].addL1 }}</span>
              <p>{{ adressData[0].addL2 }}</p>
            </address>
            <ul class="list-unstyled ul-links mb-4">
              <li>
                
                <span> <i class="fa-solid fa-phone"></i> {{ adressData[0].phone1 }}</span>
              </li>
              <li>
               
                <span> <i class="fa-solid fa-phone"></i> {{ adressData[0].phone2 }}</span>
              </li>
              <li>
                <a href="mailto:info@mydomain.com" class="d-flex">
                <span><i class="fa fa-envelope"></i> info@mydomain.com</span>
                </a>
              </li>
              <li>
              <a href="#" target="_blank" class="d-flex">
                
                <span><i class="fa-solid fa-globe"></i> https://example.com/</span>
              </a>
            </li>
            </ul>
          </div>

        </div>
      </div>
    </section><!-- End contact Section -->





</template>