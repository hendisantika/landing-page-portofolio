<template>
  <section id="portfolio" class="portfolio section">
    <h2 class="section__title">Portofolio</h2>
    <span class="section__subtitle">Most recent work</span>

    <div class="portofolio__container container swiper">
      <div class="swiper-wrapper">
        <!--==================== PORTFOLIO 1 ====================-->
        <div class="portofolio__content grid swiper-slide">
          <img alt="" class="portofolio__img" src="frontend/assets/img/1.jpeg">

          <div class="portofolio__data">
            <h3 class="portofolio__title">Modern Travel Website</h3>
            <p class="portofolio__description">Website adaptable to all devices, with ui components and
              animated interactions.
            </p>
            <a class="button button--flex button--small portofolio__button" href="https://tensholiday.com/">
              Demo
              <i class="uil uil-arrow-right button__icon"></i>
            </a>
          </div>
        </div>

        <!--==================== PORTFOLIO 2 ====================-->
        <div class="portofolio__content grid swiper-slide">
          <img alt="" class="portofolio__img" src="frontend/assets/img/2.jpeg">

          <div class="portofolio__data">
            <h3 class="portofolio__title">Modern Pesantren Website</h3>
            <p class="portofolio__description">Website adaptable to all devices, with ui components and
              animated interactions.
            </p>
            <a class="button button--flex button--small portofolio__button"
               href="https://pesantrenpersis27.com/">
              Demo
              <i class="uil uil-arrow-right button__icon"></i>
            </a>
          </div>
        </div>

        <!--==================== PORTFOLIO 3 ====================-->
        <div class="portofolio__content grid swiper-slide">
          <img alt="" class="portofolio__img" src="frontend/assets/img/3.jpeg">

          <div class="portofolio__data">
            <h3 class="portofolio__title">Modern Grafis Website</h3>
            <p class="portofolio__description">Website adaptable to all devices, with ui components and
              animated interactions.
            </p>
            <a class="button button--flex button--small portofolio__button" href="https://airygrafis.com/">
              Demo
              <i class="uil uil-arrow-right button__icon"></i>
            </a>
          </div>
        </div>

        <!--==================== PORTFOLIO 4 ====================-->
        <div class="portofolio__content grid swiper-slide">
          <img alt="" class="portofolio__img" src="frontend/assets/img/4.jpeg">

          <div class="portofolio__data">
            <h3 class="portofolio__title">Modern Machine Website</h3>
            <p class="portofolio__description">Website adaptable to all devices, with ui components and
              animated interactions.
            </p>
            <a class="button button--flex button--small portofolio__button"
               href="https://suburbaru.hilfideveloper.com/">
              Demo
              <i class="uil uil-arrow-right button__icon"></i>
            </a>
          </div>
        </div>

        <!--==================== PORTFOLIO 5 ====================-->
        <div class="portofolio__content grid swiper-slide">
          <img alt="" class="portofolio__img" src="frontend/assets/img/5.jpeg">

          <div class="portofolio__data">
            <h3 class="portofolio__title">Modern Schools Website</h3>
            <p class="portofolio__description">Website adaptable to all devices, with ui components and
              animated interactions.
            </p>
            <a class="button button--flex button--small portofolio__button"
               href="https://smkwidyadirgantara.sch.id/">
              Demo
              <i class="uil uil-arrow-right button__icon"></i>
            </a>
          </div>
        </div>

        <!--==================== PORTFOLIO 6 ====================-->
        <div class="portofolio__content grid swiper-slide">
          <img alt="" class="portofolio__img" src="frontend/assets/img/6.jpeg">

          <div class="portofolio__data">
            <h3 class="portofolio__title">Modern Wedding Website</h3>
            <p class="portofolio__description">Website adaptable to all devices, with ui components and
              animated interactions.
            </p>
            <a class="button button--flex button--small portofolio__button" href="https://risalahati.id/">
              Demo
              <i class="uil uil-arrow-right button__icon"></i>
            </a>
          </div>
        </div>
      </div>
      <!-- add arrows -->
      <div class="swiper-button-next">
        <i class="uil uil-angle-right-b swiper-portofolio-icon"></i>
      </div>
      <div class="swiper-button-prev">
        <i class="uil uil-angle-left-b swiper-portofolio-icon"></i>
      </div>

      <!-- add pagination -->
      <div class="swiper-pagination"></div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Portfolio'
}
</script>
