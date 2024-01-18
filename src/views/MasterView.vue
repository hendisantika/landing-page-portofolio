<template>
  <!--==================== HEADER ====================-->
  <header/>

  <!--==================== MAIN ====================-->
  <main class="main">
    <!--==================== HOME ====================-->
    <home/>

    <!--==================== ABOUT ====================-->
    <about/>

    <!--==================== SKILLS ====================-->
    <skills/>

    <!--==================== QUALIFICATION ====================-->
    <qualification/>

    <!--==================== SERVICES ====================-->
    <services/>

    <!--==================== PORTFOLIO ====================-->
    <portfolio/>

    <!--==================== PROJECT IN MIND ====================-->
    <project/>

    <!--==================== TESTIMONIAL ====================-->
    <testimonial/>

    <!--==================== CONTACT ME ====================-->
    <contact/>
  </main>

  <!--==================== FOOTER ====================-->
  <footer/>

  <!--==================== SCROLL TOP ====================-->
  <a id="scroll-up" class="scrollup" href="#">
    <i class="uil uil-arrow-up scrollup__icon"></i>
  </a>
</template>


<script>
import Home from './pages/HomeView.vue';
import About from './pages/AboutView.vue';
import Skills from './pages/SkillsView.vue';
import Qualification from './pages/QualificationView.vue';
import Services from './pages/ServicesView.vue';
import Portfolio from './pages/PortfolioView.vue';
import Project from './pages/ProjectView.vue';
import Testimonial from './pages/TestimonialView.vue';
import Contact from './pages/ContactView.vue';

export default {
  components: {
    Header,
    Home,
    About,
    Skills,
    Qualification,
    Services,
    Portfolio,
    Project,
    Testimonial,
    Contact,
    Footer
  },
  name: 'Master'
};
</script>
