<template>
  <div class="counter-area fix area-padding">
    <div class="container">
      <div class="row">
        <div class="col-md-6 col-sm-6 col-xs-12">
          <div class="counter-image">
            <div class="romate-image rotateme">
              <img src="/img/about/circle.png" alt=""/>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-sm-6 col-sx-12">
          <div class="fun-text-all">
            <div class="col-md-6 col-sm-6 col-sx-12">
              <div class="fun-text wow fadeInUp" data-wow-delay="o.2s">
                <span class="counter-icon"><i class="ti-layers"></i></span>
                <span class="counter">120</span>
                <h4>Client accompagnés</h4>
              </div>
            </div>
            <div class="col-md-6 col-sm-6 col-sx-12">
              <div class="fun-text wow fadeInUp" data-wow-delay="0.3s">
                <span class="counter-icon"><i class="ti-world"></i></span>
                <span class="counter">8</span>
                <h4>Années d'expérience</h4>
              </div>
            </div>
            <div class="col-md-6 col-sm-6 col-sx-12">
              <div class="fun-text wow fadeInUp" data-wow-delay="0.4s">
                <span class="counter-icon"><i class="ti-cup"></i></span>
                <span class="counter">98</span>
                <h4>de satisfaction</h4>
              </div>
            </div>
            <div class="col-md-6 col-sm-6 col-sx-12">
              <div class="fun-text wow fadeInUp" data-wow-delay="0.5s">
                <span class="counter-icon"><i class="ti-user"></i></span>
                <span class="counter">5</span>
                <h4>Formation disponibles</h4>
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
  name: "counter",
  mounted() {
    var count = $(".counter");
    count.counterUp({delay: 40, time: 3000});
  },
};
</script>

<style scoped>

</style>
