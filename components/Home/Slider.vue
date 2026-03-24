<template>
  <div class="slider-area">
   <div class="bg-wrapper">
      <img src="/img/background/bg.jpg" alt="" />
   </div>
   <div class="intro-content">
      <div class="slider-content">
          <div class="container">
              <div class="row">
                  <div class="col-md-12">
                      <div class="layer-1 wow fadeInup" data-wow-delay="0.3s">
                          <span class="title1">Votre partenaire en transformation numérique.</span>
                          <h3 class="title2">
                              <span class="color">Cabinet IT</span> -conseil, Integration <br />
                                et Formation pour votre entreprise.
                          </h3>
                      </div>
                      <div class="layer-2 wow fadeInup" data-wow-delay="0.5s">
                          <p>
                              Nous accompagnons les entreprises et organisations de lomé dans leur évolution digitale avec des soluttions IT sur mesure.
                          </p>
                      </div>
                      <div class="layer-3 wow fideInup" data-wow-delay="0.7s">
                          <nuxt-link to="/services" class="ready-btn left-btn">
                              Nos Services
                          </nuxt-link>
                          <nuxt-link to="/contact" class="ready-btn right-btn">
                              Demander un Devis
                          </nuxt-link>
                      </div>
                  </div>
              </div>
          </div>
      </div>
   </div>
  </div>
</template>

<script>
export default {
  name:"Slider",
};
</script>

<style scoped>
</style>
