<template>
  <div class="service-area bg-color area-padding-2">
    <div class="container">
      <div class="row">
        <div class="col-md-12 col-sm-12 col-sx-12">
          <div class="section-headline text-center">
            <h3>
              Nos Services IT
            </h3>
            <p>
                Nous accompagnons les entreprises dans leur transformation numérique
                avec des solutions adaptées à leurs besoins et leur budget.
            </p>
          </div>
        </div>
      </div>
    </div>


  <div class="all-services">
    <div class="row">

      <!-- Audit & Conseil IT -->
      <div class="col-md-4 col-sm-6 col-sx-12">
        <div class="single-service wow fadeinup" data-wow-delay="0.3s">
          <div class="service-icon">
            <span class="flaticon-052-project-plan"></span>
          </div>
          <div class="service-inner">
            <div class="service-content">
              <h4>
                  Audit & Conseil IT
              </h4>
              <p>
                  Évaluation de votre maturité numérique, identification
                  des risques et élaboration de feuilles de route
                  stratégiques adaptées à votre organisation.
              </p>
              <nuxt-link class="service-btn" to="/services">
                <i class="ti-arrow-right"></i>
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>

      <!-- Cloud & Infrastructure -->
      <div class="col-md-4 col-sm-6 col-sx-12">
        <div class="single-service wow fadeInup" data-wow-delay="0.3s">
          <div class="service-icon">
            <span class="flaticon-052-project-plan"></span>
          </div>
          <div class="service-inner">
            <div class="service-content">
              <h4>
                  Cloud & Infrastructure
              </h4>
              <p>
                  Migration, déploiement et optimisation d'infrastructures
                  cloud hybrides (AWS, Azure) pour fiabiliser vos systèmes
                  et réduire vos coûts opérationnels.
              </p>
              <nuxt-link class="service-btn" to="/services">
                <i class="ti-arrow-right"></i>
              </nuxt-link>
            </div>
          </div>
        </div>
    </div>


      <!-- Cybersécurité -->
     <div class="col-md-4 col-sm-6 col-sx-12">
        <div class="single-service wow fadeInup" data-wow-delay="0.3s">
          <div class="service-icon">
            <span class="flaticon-052-project-plan"></span>
          </div>
          <div class="service-inner">
            <div class="service-content">
              <h4>
                  Cybersécurité
              </h4>
              <p>
                  Protection de votre patrimoine numérique : tests
                  d'intrusion, audit de conformité ISO 27001, mise en place
                  de politiques de sécurité et sensibilisation des équipes.
              </p>
              <nuxt-link class="service-btn" to="/services">
                <i class="ti-arrow-right"></i>
              </nuxt-link>
            </div>
          </div>
        </div>
    </div>


    <!-- Development -->
     <div class="col-md-4 col-sm-6 col-sx-12">
        <div class="single-service wow fadeInup" data-wow-delay="0.3s">
          <div class="service-icon">
            <span class="flaticon-052-project-plan"></span>
          </div>
          <div class="service-inner">
            <div class="service-content">
              <h4>
                  Development
              </h4>
              <p>
                  Conception et développement d'applications web et mobiles
                  qui automatisent vos processus métier et améliorent
                  l'expérience de vos utilisateurs.
              </p>
              <nuxt-link class="service-btn" to="/services">
                <i class="ti-arrow-right"></i>
              </nuxt-link>
            </div>
          </div>
        </div>
    </div>

      <!-- Data & BI -->
     <div class="col-md-4 col-sm-6 col-sx-12">
        <div class="single-service wow fadeInup" data-wow-delay="0.3s">
          <div class="service-icon">
            <span class="flaticon-052-project-plan"></span>
          </div>
          <div class="service-inner">
            <div class="service-content">
              <h4>
                  Data & Business Intelligence
              </h4>
              <p>
                  Transformez vos données en décisions grâce à des tableaux
                  de bord temps réel, des entrepôts de données et des
                  modèles d'analyse prédictive (Power BI, Python).
              </p>
              <nuxt-link class="service-btn" to="/services">
                <i class="ti-arrow-right"></i>
              </nuxt-link>
            </div>
          </div>
        </div>
    </div>


        <!--Support & Maintenance -->
     <div class="col-md-4 col-sm-6 col-sx-12">
        <div class="single-service wow fadeInup" data-wow-delay="0.3s">
          <div class="service-icon">
            <span class="flaticon-052-project-plan"></span>
          </div>
          <div class="service-inner">
            <div class="service-content">
              <h4>
                  Support & Maintenance
              </h4>
              <p>
                 Assistance technique N1/N2/N3 et tierce maintenance
                applicative pour garantir la continuité de vos systèmes
                avec des SLA adaptés à vos besoins.
              </p>
              <nuxt-link class="service-btn" to="/services">
                <i class="ti-arrow-right"></i>
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
  name: "Service",
};
</script>

<style scoped>
</style>

