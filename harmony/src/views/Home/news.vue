<template>
    <!-- ======= About Boxes Section ======= -->
    <section id="about-boxes" class="about-boxes">
        <div class="container" data-aos="fade-up">
            <h2 class="text-center fw-bold pb-3">News</h2>
            <div class="row">
                <div class="col-lg-4 col-md-6 d-flex align-items-stretch" data-aos="fade-up" data-aos-delay="100">
                    <div class="card">
                        <img src="@/assets/images/about-boxes-1.jpg" class="card-img-top" alt="...">
                        <div class="card-icon">
                            <i class="ri-brush-4-line"></i>
                        </div>
                        <div class="card-body">
                            <h5 class="card-title"><a href="">Our Mission</a></h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur elit, sed do eiusmod tempor ut
                                labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                                ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 d-flex align-items-stretch" data-aos="fade-up" data-aos-delay="200">
                    <div class="card">
                        <img src="@/assets/images/about-boxes-2.jpg" class="card-img-top" alt="...">
                        <div class="card-icon">
                            <i class="ri-calendar-check-line"></i>
                        </div>
                        <div class="card-body">
                            <h5 class="card-title"><a href="">Our Plan</a></h5>
                            <p class="card-text">Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                                doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et
                                quasi architecto beatae vitae dicta sunt explicabo. </p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 d-flex align-items-stretch" data-aos="fade-up" data-aos-delay="300">
                    <div class="card">
                        <img src="@/assets/images/about-boxes-3.jpg" class="card-img-top" alt="...">
                        <div class="card-icon">
                            <i class="ri-movie-2-line"></i>
                        </div>
                        <div class="card-body">
                            <h5 class="card-title"><a href="">Our Vision</a></h5>
                            <p class="card-text">Nemo enim ipsam voluptatem quia voluptas sit aut odit aut fugit, sed
                                quia magni dolores eos qui ratione voluptatem sequi nesciunt Neque porro quisquam est,
                                qui dolorem ipsum quia dolor sit amet. </p>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section><!-- End About Boxes Section -->
</template>
<style scope>
.about-boxes {
  background: url("@/assets/images/about-boxes-bg.jpg") center top no-repeat fixed;
  background-size: cover;
  padding: 40px 0 30px 0;
  position: relative;
}

.about-boxes::before {
  content: "";
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  background: rgba(255, 255, 255, 0.92);
  z-index: 9;
}

.about-boxes .container,
.about-boxes .container-fluid {
  position: relative;
  z-index: 10;
}

.about-boxes .card {
  border-radius: 3px;
  border: 0;
  box-shadow: 0px 2px 15px rgba(0, 0, 0, 0.1);
  margin-bottom: 30px;
}

.about-boxes .card-icon {
  text-align: center;
  margin-top: -32px;
}

.about-boxes .card-icon i {
  font-size: 32px;
  color: #fff;
  width: 64px;
  height: 64px;
  padding-top: 5px;
  text-align: center;
  background-color: #ff4a17;
  border-radius: 4px;
  text-align: center;
  border: 4px solid #fff;
  transition: 0.3s;
  display: inline-block;
}

.about-boxes .card-body {
  padding-top: 12px;
}

.about-boxes .card-title {
  font-weight: 700;
  text-align: center;
}

.about-boxes .card-title a {
  color: #15222b;
}

.about-boxes .card-title a:hover {
  color: #ff4a17;
}

.about-boxes .card-text {
  color: #5e5e5e;
}

.about-boxes .card:hover .card-icon i {
  background: #fff;
  color: #ff4a17;
}

@media (max-width: 1024px) {
  .about-boxes {
    background-attachment: scroll;
  }
}
</style>