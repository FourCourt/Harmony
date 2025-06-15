<template>
  <section id="hero">
    <div class="hero-container" data-aos="fade-up" data-aos-delay="150">
      <h1>Plan. Launch. Grow.</h1>
      <h2>We are team of talented designers making websites with Bootstrap</h2>
      <div class="d-flex">
        <a href="#about" class="btn-get-started scrollto">Get Started</a>
        <a href="https://www.youtube.com/watch?v=jDDaplaOz7Q" class="glightbox btn-watch-video"><i
            class="bi bi-play-circle"></i><span>Watch Video</span></a>
      </div>
    </div>
  </section><!-- End Hero -->
</template>

<script setup>
import { onMounted } from 'vue'
import GLightbox from 'glightbox'
import 'glightbox/dist/css/glightbox.css'

onMounted(() => {
  GLightbox()
})

</script>

<style scoped>
/*--------------------------------------------------------------
# Hero Section
--------------------------------------------------------------*/
#hero {
  width: 100%;
  height: 100vh;
  background: url("@/assets/images/hero-bg.jpg") top center;
  background-size: cover;
  position: relative;
  padding: 0;
}

#hero:before {
  content: "";
  background: rgba(13, 20, 26, 0.7);
  position: absolute;
  bottom: 0;
  top: 0;
  left: 0;
  right: 0;
}

#hero .hero-container {
  position: absolute;
  bottom: 0;
  top: 0;
  left: 0;
  right: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
}

#hero h1 {
  margin: 0 0 10px 0;
  font-size: 48px;
  font-weight: 700;
  line-height: 56px;
  text-transform: uppercase;
  color: #fff;
}

#hero h2 {
  color: #eee;
  margin-bottom: 50px;
  font-size: 24px;
}

#hero .btn-get-started {
  font-family: "Open Sans", sans-serif;
  text-transform: uppercase;
  font-weight: 500;
  font-size: 14px;
  display: inline-block;
  padding: 10px 35px 10px 35px;
  border-radius: 4px;
  transition: 0.5s;
  color: #fff;
  background: #ff4a17;
  border: 2px solid #ff4a17;
}

#hero .btn-get-started:hover {
  border-color: #fff;
  background: rgba(255, 255, 255, 0.1);
}

#hero .btn-watch-video {
  font-size: 16px;
  display: inline-block;
  transition: 0.5s;
  margin-left: 25px;
  color: #fff;
  display: inline-flex;
  align-items: center;
  justify-content: center;
}

#hero .btn-watch-video i {
  line-height: 0;
  color: #fff;
  font-size: 32px;
  transition: 0.3s;
  margin-right: 8px;
}

#hero .btn-watch-video:hover i {
  color: #ff4a17;
}

@media (min-width: 1024px) {
  #hero {
    background-attachment: fixed;
  }
}

@media (max-width: 768px) {
  #hero h1 {
    font-size: 28px;
    line-height: 36px;
  }

  #hero h2 {
    font-size: 18px;
    line-height: 24px;
    margin-bottom: 30px;
  }
}
</style>