<template>
  <div id="main-wrapper" class="main-wrapper">
    <nav class="navbar sticky-top navbar-expand-lg bg-dark">
      <div class="container">
        <a class="navbar-brand" href="#" style="height: 75px">
          <img :src="carLogo" alt="logo" class="h-100" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarToggleExternalContent"
          aria-controls="navbarToggleExternalContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarToggleExternalContent">
          <ul class="navbar-nav mr-auto w-100 justify-content-end">
            <li class="nav-item active">
              <a class="nav-link" href="#main-wrapper">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about-section">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#service-section">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#price-section">Price</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact-section">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- nav bar end -->
    <!-- crousle start here -->
    <div
      id="carouselExampleCaptions"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img :src="carousel1" class="d-block w-100" alt="..." />
          <div class="carousel-caption d-none d-md-block">
            <h5>First slide label</h5>
            <p>Some representative placeholder content for the first slide.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img :src="carousel2" class="d-block w-100" alt="..." />
          <div class="carousel-caption d-none d-md-block">
            <h5>Second slide label</h5>
            <p>Some representative placeholder content for the second slide.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img :src="carousel3" class="d-block w-100" alt="..." />
          <div class="carousel-caption d-none d-md-block">
            <h5>Third slide label</h5>
            <p>Some representative placeholder content for the third slide.</p>
          </div>
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <!-- crousle end here -->
    <!-- about start here -->
    <div id="about-section" class="about">
      <div class="main-container">
        <div class="row align-items-center">
          <div class="col-lg-6">
            <div class="about-img">
              <img :src="about" alt="Image" />
            </div>
          </div>
          <div class="col-lg-6">
            <div class="section-header text-left">
              <p>About Us</p>
              <h2>car washing and detailing</h2>
            </div>
            <div class="about-content">
              <p>
                Lorem ipsum dolor sit amet elit. In vitae turpis. Donec in
                hendre dui, vel blandit massa. Ut vestibu suscipi cursus. Cras
                quis porta nulla, ut placerat risus. Aliquam nec magna eget
                velit luctus dictum Lorem ipsum dolor sit amet elit. In vitae
                turpis. Donec in hendre dui, vel blandit massa. Ut vestibu
                suscipi cursus. Cras quis porta nulla, ut placerat risus.
                Aliquam nec magna eget velit luctus dictum
              </p>
              <ul>
                <li><i class="far fa-check-circle"></i>Seats washing</li>
                <li><i class="far fa-check-circle"></i>Vacuum cleaning</li>
                <li>
                  <i class="far fa-check-circle"></i>Interior wet cleaning
                </li>
                <li><i class="far fa-check-circle"></i>Window wiping</li>
              </ul>
              <!-- <a class="btn btn-custom" href="">Learn More</a> -->
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- about end here -->

    <!-- service start here -->
    <div id="service-section" class="service">
      <div class="main-container">
        <div class="section-header text-center">
          <p>What We Do?</p>
          <h2>Premium Washing Services</h2>
        </div>
        <div class="row">
          <div class="col-lg-3 col-md-6">
            <div class="service-item">
              <img :src="exteriorWashing" alt="logo" class="service-item-img" />
              <h3>Exterior Washing</h3>
              <p>
                Lorem ipsum dolor sit amet elit. Phase nec preti facils ornare
                velit non metus tortor
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="service-item">
              <img :src="interiorWashing" alt="logo" class="service-item-img" />
              <h3>Interior Washing</h3>
              <p>
                Lorem ipsum dolor sit amet elit. Phase nec preti facils ornare
                velit non metus tortor
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="service-item">
              <img :src="vacummCleaning" alt="logo" class="service-item-img" />
              <h3>Vacuum Cleaning</h3>
              <p>
                Lorem ipsum dolor sit amet elit. Phase nec preti facils ornare
                velit non metus tortor
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="service-item">
              <img :src="seatsWashing" alt="logo" class="service-item-img" />
              <h3>Seats Washing</h3>
              <p>
                Lorem ipsum dolor sit amet elit. Phase nec preti facils ornare
                velit non metus tortor
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="service-item">
              <img :src="windowWiping" alt="logo" class="service-item-img" />
              <h3>Window Wiping</h3>
              <p>
                Lorem ipsum dolor sit amet elit. Phase nec preti facils ornare
                velit non metus tortor
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="service-item">
              <img :src="wetCleaning" alt="logo" class="service-item-img" />
              <h3>Wet Cleaning</h3>
              <p>
                Lorem ipsum dolor sit amet elit. Phase nec preti facils ornare
                velit non metus tortor
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="service-item">
              <img :src="oilChanging" alt="logo" class="service-item-img" />
              <h3>Oil Changing</h3>
              <p>
                Lorem ipsum dolor sit amet elit. Phase nec preti facils ornare
                velit non metus tortor
              </p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="service-item">
              <img :src="brakeReparing" alt="logo" class="service-item-img" />
              <h3>Brake Reparing</h3>
              <p>
                Lorem ipsum dolor sit amet elit. Phase nec preti facils ornare
                velit non metus tortor
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- service end here -->
    <!-- facts start here -->
    <div class="facts" data-parallax="scroll" data-image-src="img/facts.jpg">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 col-md-6">
            <div class="facts-item">
              <i class="fa fa-map-marker-alt"></i>
              <div class="facts-text">
                <h3 data-toggle="counter-up">25</h3>
                <p>Service Points</p>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="facts-item">
              <i class="fa fa-user"></i>
              <div class="facts-text">
                <h3 data-toggle="counter-up">350</h3>
                <p>Engineers &amp; Workers</p>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="facts-item">
              <i class="fa fa-users"></i>
              <div class="facts-text">
                <h3 data-toggle="counter-up">1500</h3>
                <p>Happy Clients</p>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="facts-item">
              <i class="fa fa-check"></i>
              <div class="facts-text">
                <h3 data-toggle="counter-up">5000</h3>
                <p>Projects Completed</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- facts end here -->
    <!-- plan start here  -->
    <div id="price-section" class="price">
      <div class="main-container">
        <div class="section-header text-center">
          <p>Washing Plan</p>
          <h2>Choose Your Plan</h2>
        </div>
        <div class="row">
          <div class="col-md-4">
            <div class="price-item featured-item p-3">
              <div class="border hover-border-change">
                <div class="price-header">
                  <h3>Basic Cleaning</h3>
                  <h2><span>$</span><strong>25</strong><span>.99</span></h2>
                </div>
                <div class="price-body">
                  <ul>
                    <li><i class="far fa-check-circle"></i>Seats Washing</li>
                    <li><i class="far fa-check-circle"></i>Vacuum Cleaning</li>
                    <li>
                      <i class="far fa-check-circle"></i>Exterior Cleaning
                    </li>
                    <li>
                      <i class="far fa-times-circle"></i>Interior Wet Cleaning
                    </li>
                    <li><i class="far fa-times-circle"></i>Window Wiping</li>
                  </ul>
                </div>
                <div class="price-footer">
                  <a
                    class="btn btn-custom"
                    href="https://wa.me/8299001059/?text=hello-Message"
                    >Book Now</a
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="price-item featured-item p-3">
              <div class="border hover-border-change">
                <div class="price-header">
                  <h3>Premium Cleaning</h3>
                  <h2><span>$</span><strong>35</strong><span>.99</span></h2>
                </div>
                <div class="price-body">
                  <ul>
                    <li><i class="far fa-check-circle"></i>Seats Washing</li>
                    <li><i class="far fa-check-circle"></i>Vacuum Cleaning</li>
                    <li>
                      <i class="far fa-check-circle"></i>Exterior Cleaning
                    </li>
                    <li>
                      <i class="far fa-check-circle"></i>Interior Wet Cleaning
                    </li>
                    <li><i class="far fa-times-circle"></i>Window Wiping</li>
                  </ul>
                </div>
                <div class="price-footer">
                  <a
                    class="btn btn-custom"
                    href="https://wa.me/8299001059/?text=hello-Message2"
                    >Book Now</a
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="price-item featured-item p-3">
              <div class="border hover-border-change">
                <div class="price-header">
                  <h3>Complex Cleaning</h3>
                  <h2><span>$</span><strong>49</strong><span>.99</span></h2>
                </div>
                <div class="price-body">
                  <ul>
                    <li><i class="far fa-check-circle"></i>Seats Washing</li>
                    <li><i class="far fa-check-circle"></i>Vacuum Cleaning</li>
                    <li>
                      <i class="far fa-check-circle"></i>Exterior Cleaning
                    </li>
                    <li>
                      <i class="far fa-check-circle"></i>Interior Wet Cleaning
                    </li>
                    <li><i class="far fa-check-circle"></i>Window Wiping</li>
                  </ul>
                </div>
                <div class="price-footer">
                  <a
                    class="btn btn-custom"
                    href="https://wa.me/8299001059/?text=hello-Message3"
                    >Book Now</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- plan end here -->
    <!-- location start here -->
    <div id="contact-section" class="location">
      <div class="main-container">
        <div class="row">
          <div class="col-lg-7">
            <div class="section-header text-left">
              <p>Washing Points</p>
              <h2>Car Washing &amp; Care Points</h2>
            </div>
            <div class="row">
              <div class="col-md-6">
                <div class="location-item">
                  <img :src="pin" alt="logo" class="" style="" />
                  <!-- <i class="fa fa-map-marker-alt"></i> -->
                  <div class="location-text">
                    <h3>Car Washing Point</h3>
                    <p>123 Street, New York, USA</p>
                    <p><strong>Call:</strong>+012 345 6789</p>
                  </div>
                </div>
              </div>
              <!-- <div class="col-md-6">
                <div class="location-item">
                  <i class="fa fa-map-marker-alt"></i>
                  <div class="location-text">
                    <h3>Car Washing Point</h3>
                    <p>123 Street, New York, USA</p>
                    <p><strong>Call:</strong>+012 345 6789</p>
                  </div>
                </div>
              </div>
              <div class="col-md-6">
                <div class="location-item">
                  <i class="fa fa-map-marker-alt"></i>
                  <div class="location-text">
                    <h3>Car Washing Point</h3>
                    <p>123 Street, New York, USA</p>
                    <p><strong>Call:</strong>+012 345 6789</p>
                  </div>
                </div>
              </div>
              <div class="col-md-6">
                <div class="location-item">
                  <i class="fa fa-map-marker-alt"></i>
                  <div class="location-text">
                    <h3>Car Washing Point</h3>
                    <p>123 Street, New York, USA</p>
                    <p><strong>Call:</strong>+012 345 6789</p>
                  </div>
                </div>
              </div> -->
            </div>
          </div>
          <div class="col-lg-5">
            <div class="location-form">
              <h3>Request for a car wash</h3>
              <form>
                <div class="control-group">
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Name"
                    required="required"
                  />
                </div>
                <div class="control-group">
                  <input
                    type="email"
                    class="form-control"
                    placeholder="Email"
                    required="required"
                  />
                </div>
                <div class="control-group">
                  <textarea
                    class="form-control"
                    placeholder="Description"
                    required="required"
                  ></textarea>
                </div>
                <div>
                  <button class="btn btn-custom" type="submit">
                    Send Request
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- location end here -->
    <!-- footer start here -->
    <div class="footer">
      <div class="main-container copyright">
        <p>© <a href="#">My shop name</a>, All Right Reserved</p>
      </div>
    </div>
    <!-- footer end here -->
  </div>
</template>

<script>
import Carousel1 from "@/assets/carousel-1.jpg";
import Carousel2 from "@/assets/carousel-2.jpg";
import Carousel3 from "@/assets/carousel-3.jpg";
import CarLogo from "@/assets/car-logo.png";
import BrakeReparing from "@/assets/brake-reparing.png";
import OilChanging from "@/assets/oil-changing.png";
import WetCleaning from "@/assets/wet-cleaning.png";
import WindowWiping from "@/assets/window-wiping.png";
import SeatsWashing from "@/assets/seats-washing.png";
import VacummCleaning from "@/assets/vacumm-cleaning.png";
import InteriorWashing from "@/assets/interior-washing.png";
import ExteriorWashing from "@/assets/exterior-washing.png";
import Pin from "@/assets/pin.png";
import About from "@/assets/about.jpg";

export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data() {
    return {
      carousel1: Carousel1,
      carousel2: Carousel2,
      carousel3: Carousel3,
      carLogo: CarLogo,
      brakeReparing: BrakeReparing,
      oilChanging: OilChanging,
      wetCleaning: WetCleaning,
      windowWiping: WindowWiping,
      seatsWashing: SeatsWashing,
      vacummCleaning: VacummCleaning,
      interiorWashing: InteriorWashing,
      exteriorWashing: ExteriorWashing,
      pin: Pin,
      about: About,
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #4cc1bb;
}
.sticky-top {
  background-color: #ffffff !important;
  border-bottom: 1px solid #ccc;
  color: #4cc1bb;
}
.carousel {
  position: relative;
  max-height: 500px;
  margin: 0 auto;
  height: 500px;
  max-width: 92%;
  margin-top: 15px;
}
.main-container {
  max-width: 92%;
  margin: 0 auto;
}
.carousel-inner {
  position: relative;
  width: 100%;
  overflow: hidden;
  height: 100%;
  max-height: 100%;
}
.carousel-item,
.carousel-item img {
  height: 100%;
  max-height: 100%;
}

.price-item.featured-item:hover .hover-border-change {
  border-color: #e81c2e !important;
}
.service-item-img {
  height: 75px !important;
  width: auto;
  margin-bottom: 20px;
}
.service .service-item h3 {
  margin-bottom: 10px;
  font-size: 20px;
  font-weight: 700;
  letter-spacing: 1px;
}
.facts {
  position: relative;
  width: 100%;
  min-height: 400px;
  margin: 45px 0;
  display: flex;
  align-items: center;
  background: #202c45;
}
.location {
  position: relative;
  width: 100%;
  padding: 45px 0;
}
.location .location-form {
  padding: 45px 30px;
  background: #e81c2e;
  border-radius: 5px;
}
.location .location-form h3 {
  color: #ffffff;
  font-size: 25px;
  font-weight: 700;
  margin-bottom: 25px;
}
.location .location-form .control-group {
  margin-bottom: 15px;
}
.form-control {
  display: block;
  width: 100%;
  height: calc(1.5em + 0.75rem + 2px);
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #495057;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ced4da;
  border-radius: 0.25rem;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}
.location .location-form .form-control {
  height: 45px;
  color: #ffffff;
  padding: 0 15px;
  border-radius: 5px;
  border: 1px solid #ffffff;
  background: transparent;
}
.location .location-form textarea.form-control {
  height: 120px;
  padding: 15px;
}
.btn.btn-custom {
  padding: 10px 30px 12px 30px;
  text-align: center;
  font-size: 16px;
  font-weight: 500;
  color: #ffffff;
  background: #e81c2e;
  border: none;
  border-radius: 60px;
  box-shadow: inset 0 0 0 0 #202c45;
  transition: ease-out 0.5s;
  -webkit-transition: ease-out 0.5s;
  -moz-transition: ease-out 0.5s;
}
.location .location-form .btn.btn-custom {
  width: 100%;
  color: #e81c2e;
  background: #ffffff;
  box-shadow: inset 0 0 0 0 #202c45;
}
.location ::placeholder {
  color: #ffffff;
  opacity: 1; /* Firefox */
}

.location ::-ms-input-placeholder {
  /* Edge 12-18 */
  color: #ffffff;
}
.location .location-item {
  display: flex;
  margin-bottom: 30px;
}
.location .location-item img {
  padding-top: 3px;
  width: 40px;
  height: 40px;
}
.location .location-text {
  padding-left: 15px;
}
.location .location-text h3 {
  font-size: 18px;
  font-weight: 700;
}
.location .location-text p {
  margin-bottom: 5px;
}
.section-header p {
  display: inline-block;
  margin-bottom: 10px;
  padding-bottom: 5px;
  position: relative;
  font-size: 16px;
  font-weight: 700;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #e81c2e;
}
.section-header p::after {
  position: absolute;
  content: "";
  width: 50%;
  height: 2px;
  left: 25%;
  bottom: 0;
  background: #e81c2e;
}
.section-header.text-left p::after {
  left: 0;
}
.facts .facts-text {
  padding-left: 20px;
}
.facts .facts-text h3 {
  position: relative;
  display: inline-block;
  color: #ffffff;
  font-size: 60px;
  font-weight: 700;
}
.facts .facts-text h3::after {
  position: absolute;
  content: "\002B";
  top: 0px;
  right: -25px;
  color: #ffffff;
  font-size: 25px;
  font-family: "Font Awesome 5 Free";
  font-weight: 900;
}
.facts .facts-text p {
  color: #ffffff;
  font-size: 18px;
  font-weight: 500;
  margin: 0;
}
.footer {
  position: relative;
  margin-top: 45px;
  padding-top: 15px;
  background: #202c45;
}
.footer .copyright {
  text-align: center;
  padding-top: 15px;
  padding-bottom: 15px;
}
.footer .copyright p {
  margin: 0;
  color: #ffffff;
}
.price {
  position: relative;
  width: 100%;
  padding: 45px 0 15px 0;
}
.section-header {
  position: relative;
  width: 100%;
  max-width: 700px;
  margin: 0 auto 45px auto;
}
.section-header p {
  display: inline-block;
  margin-bottom: 10px;
  padding-bottom: 5px;
  position: relative;
  font-size: 16px;
  font-weight: 700;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #e81c2e;
}
.section-header p::after {
  position: absolute;
  content: "";
  width: 50%;
  height: 2px;
  left: 25%;
  bottom: 0;
  background: #e81c2e;
}
.section-header h2 {
  margin: 0;
  font-size: 45px;
  font-weight: 700;
  text-transform: capitalize;
}
.price .price-item {
  position: relative;
  margin-bottom: 30px;
  background: #ffffff;
  border-radius: 5px;
  text-align: center;
  transition: transform 0.3s ease-in-out;
}
.price-item.featured-item:hover {
  transform: scale(1.03);
}
.price .price-header {
  padding: 45px 0 30px 0;
}
.price .price-header h3 {
  font-size: 20px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
}
.price .price-header h2 {
  display: flex;
  align-items: flex-start;
  justify-content: center;
  font-size: 60px;
  font-weight: 700;
  letter-spacing: 5px;
}
.price .price-header h2 span {
  font-size: 25px;
  line-height: 55px;
}
.price .price-item .price-footer {
  padding-bottom: 45px;
}
.price .price-item.featured-item .price-footer .btn.btn-custom {
  color: #fff;
  background: #e81c2e;
  box-shadow: inset 0 0 0 0 #202c45;
}
.price .price-body {
  padding: 0 0 20px 0;
}
.price .price-body ul {
  margin: 0;
  padding: 0;
  list-style: none;
}
.price .price-body ul li {
  padding: 0 0 15px 0;
}
.price .price-body ul li i.fa-check-circle {
  color: #39b972;
}
.price .price-body ul li i {
  margin-right: 10px;
}
.price .price-item.featured-item h2,
.price .price-item.featured-item h3 {
  color: #e81c2e;
}
.price .price-item .price-footer .btn.btn-custom {
  color: #e81c2e;
  background: #202c45;
  box-shadow: inset 0 0 0 0 #e81c2e;
}
.price .price-item.featured-item .price-footer .btn.btn-custom {
  color: #fff;
  background: #e81c2e;
  box-shadow: inset 0 0 0 0 #202c45;
}
.facts .facts-item {
  display: flex;
  flex-direction: row;
  margin: 25px 0;
}
.facts .facts-item svg {
  margin-top: 15px;
  font-size: 45px;
  color: #e81c2e;
}
.price .featured-item {
  box-shadow: 0 0 30px rgba(0, 0, 0, 0.2);
  z-index: 1;
}
.price .price-item {
  position: relative;
  margin-bottom: 30px;
  background: #ffffff;
  border-radius: 5px;
  text-align: center;
}
.about {
  position: relative;
  width: 100%;
  padding: 45px 0 15px;
}
.about .about-img img {
  width: 100%;
  border-radius: 5px;
  margin-bottom: 30px;
}
.about .section-header {
  margin-bottom: 30px;
  margin-left: 0;
}
.section-header {
  position: relative;
  width: 100%;
  max-width: 700px;
  margin: 0 auto 45px;
}
.section-header p {
  display: inline-block;
  margin-bottom: 10px;
  padding-bottom: 5px;
  position: relative;
  font-size: 16px;
  font-weight: 700;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #e81c2e;
}
.about .about-content {
  margin-bottom: 30px;
}
.about .about-content ul {
  margin: 0;
  padding: 0;
  list-style: none;
  margin-bottom: 25px;
  padding-bottom: 70px;
}
.about .about-content ul li {
  margin-bottom: 15px;
  width: 100%;
}
.about .about-content ul li svg {
  margin-right: 8px;
  color: #e81c2e;
}
.btn.btn-custom {
  padding: 10px 30px 12px;
  text-align: center;
  font-size: 16px;
  font-weight: 500;
  color: #fff;
  background: #e81c2e;
  border: none;
  border-radius: 60px;
  box-shadow: inset 0 0 0 0 #202c45;
  transition: ease-out 0.5s;
  -webkit-transition: ease-out 0.5s;
  -moz-transition: ease-out 0.5s;
}
</style>
