<template>
  <section id="contact" class="contact section">
    <h2 class="section__title">Contact Me</h2>
    <span class="section__subtitle">Get in Touch</span>

    <div class="contact__container container grid">
      <div>
        <div class="contact__information">
          <i class="uil uil-phone contact__icon"></i>

          <div>
            <h3 class="contact__title">Call me</h3>
            <span class="contact__subtitle">081914209656</span>
          </div>
        </div>

        <div class="contact__information">
          <i class="uil uil-envelope contact__icon"></i>

          <div>
            <h3 class="contact__title">Email</h3>
            <span class="contact__subtitle">hilmanfirdaus48@gmail.com</span>
          </div>
        </div>

        <div class="contact__information">
          <i class="uil uil-map-marker contact__icon"></i>

          <div>
            <h3 class="contact__title">Location</h3>
            <span class="contact__subtitle">Cigondewah - Kota Bandung</span>
          </div>
        </div>
      </div>

      <form action="" class="contact__form grid">
        <div class="contact__inputs grid">
          <div class="contact__content">
            <label class="contact__label" for="">Name</label>
            <input class="contact__input" type="text">
          </div>
          <div class="contact__content">
            <label class="contact__label" for="">Email</label>
            <input class="contact__input" type="email">
          </div>
        </div>
        <div class="contact__content">
          <label class="contact__label" for="">Project</label>
          <input class="contact__input" type="text">
        </div>
        <div class="contact__content">
          <label class="contact__label" for="">Message</label>
          <textarea id="" class="contact__input" cols="0" name="" rows="7"></textarea>
        </div>

        <div>
          <a class="button button--flex" href="">
            Send Message
            <i class="uil uil-message button__icon"></i>
          </a>
        </div>
      </form>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Contact'
}
</script>
