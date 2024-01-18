<template>
  <header id="header" class="header">
    <nav class="nav container">
      <a class="nav__logo" href="#">Hendi Santika</a>

      <div id="nav-menu" class="nav__menu">
        <ul class="nav__list grid">
          <li class="nav__item">
            <a class="nav__link active-link" href="#home">
              <i class="uil uil-estate nav__icon"></i> Home
            </a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#about">
              <i class="uil uil-user nav__icon"></i> About
            </a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#skills">
              <i class="uil uil-file-alt nav__icon"></i> Skills
            </a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#services">
              <i class="uil uil-briefcase-alt nav__icon"></i> Services
            </a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#portfolio">
              <i class="uil uil-scenery nav__icon"></i> Portfolio
            </a>
          </li>
          <li class="nav__item">
            <a class="nav__link" href="#contact">
              <i class="uil uil-message nav__icon"></i> Contact Me
            </a>
          </li>
        </ul>
        <i id="nav-close" class="uil uil-times nav__close"></i>
      </div>

      <div class="nav__btns">
        <!-- theme change button -->
        <i id="theme-button" class="uil uil-moon change-theme"></i>
        <div id="nav-toggle" class="nav__toggle">
          <i class="uil uil-apps"></i>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>
