<template>
  <section id="about" class="about section">
    <h2 class="section__title">About Me</h2>
    <span class="section__subtitle">My Introduction</span>

    <div class="about__container container grid">
      <img alt="" class="about__img" src="frontend/assets/img/hendi.jpeg">

      <div class="about__data">
        <p class="about__description">Web developer with extensive knowledge and years of experience, working
          in Backend things, web technologies and Ui / Ux design with delivering quality work.
        </p>

        <div class="about__info">
          <div>
            <span class="about__info-title">15+</span>
            <span class="about__info-name">Years <br> experience</span>
          </div>
          <div>
            <span class="about__info-title">50+</span>
            <span class="about__info-name">Completed <br> project</span>
          </div>
          <div>
            <span class="about__info-title">10+</span>
            <span class="about__info-name">Companies <br> worked</span>
          </div>
        </div>

        <div class="about__buttons">
          <a class="button button--flex" download="" href="frontend/assets/pdf/CV_HendiSantika_SEPT_2023.pdf">
            Download CV<i class="uil uil-download-alt button__icon"></i>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>


<script>
export default {
  name: 'About'
};
</script>
