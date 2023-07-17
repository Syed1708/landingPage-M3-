
<script setup>
const pricingData = [
    {
        title: "Pricing",
        description: "Pricing for everyone. Choose your plan now!"
    },


]

</script>

<template>
    
    <!-- ======= Pricing Section ======= -->
    <section id="pricing" class="pricing">
      <div class="container" data-aos="fade-up">

        <div class="section-title">
          <h2>{{ pricingData[0].title }}</h2>
          <p>{{ pricingData[0].description }}</p>
        </div>

        <div class="row row-cols-1 row-cols-md-3 mb-3 text-center">
          <div class="col">
            <div class="card mb-4 rounded-3 shadow-sm">
              <div class="card-header py-3">
                <h4 class="my-0 fw-normal">Free</h4>
              </div>
              <div class="card-body">
                <h1 class="card-title pricing-card-title">$0</h1>
                <ul class="list-unstyled mt-3 mb-4">
                  <li>>> There live the blind texts</li>
                  <li>>> Far far away behind the word</li>
                  <li>Far from the countries Vokalia and Consonantia</li>
                  <li>Email support</li>
                  <li>Help center access</li>
                </ul>
                <button type="button" class="w-100 btn btn-lg btn-outline-primary">Get Started</button>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card mb-4 rounded-3 shadow-sm">
              <div class="card-header py-3">
                <h4 class="my-0 fw-normal">Pro</h4>
              </div>
              <div class="card-body">
                <h1 class="card-title pricing-card-title">$15</h1>
                <ul class="list-unstyled mt-3 mb-4">
                  <li>>> There live the blind texts</li>
                  <li>>> Far far away behind the word</li>
                  <li>Far from the countries Vokalia and Consonantia</li>
                  <li>Email support</li>
                  <li>Help center access</li>
                </ul>
                <button type="button" class="w-100 btn btn-lg btn-outline-primary">Get started</button>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card mb-4 rounded-3 shadow-sm border-primary">
              <div class="card-header py-3 text-bg-primary border-primary">
                <h4 class="my-0 fw-normal">Enterprise</h4>
              </div>
              <div class="card-body">
                <h1 class="card-title pricing-card-title">$29</h1>
                <ul class="list-unstyled mt-3 mb-4">
                  <li>There live the blind texts</li>
                  <li>Far far away behind the word</li>
                  <li>Far from the countries Vokalia and Consonantia</li>
                  <li>Email support</li>
                  <li>Help center access</li>
                </ul>
                <button type="button" class="w-100 btn btn-lg btn-outline-primary">Contact us</button>
              </div>
            </div>
          </div>
        </div>

      </div>
    </section><!-- End pricing Section -->

</template>