<template>
  <div>

  <!-- ======= Header ======= -->
  <header id="header" class="fixed-top ">
    <div class="container-fluid">

      <div class="row justify-content-center">
        <div class="col-xl-9 d-flex align-items-center justify-content-between">
         <!-- <h1 class="logo"><a href="/"><span>CARE AND COMFORT</span></a></h1> -->
           <h1 class="logo mr-auto"><nuxt-link  :to="{ path: '/'}">
      <span><img src="../assets/img/cnc/cnc_logo2.png" class="logo-img" alt=""></span>
      </nuxt-link></h1>
          <!-- Uncomment below if you prefer to use an image logo -->
          <!--<a href="index.html" class="logo"><img src="../assets/img/logo.jpg" alt="" class="img-fluid"></a>-->

          <nav class="nav-menu d-none d-lg-block">
            <ul>
              <li class="active"><a href="#hero">Home</a></li>
              <li><a href="#about">About</a></li>
              <li><a href="#services">Services</a></li>

              <li><a href="#contact">Contact</a></li>

            </ul>
          </nav><!-- .nav-menu -->

        <!--  <a href="/care_and_comfort_brochure.pdf" class="get-started-btn scrollto" target="_blank">Brochure</a> -->
        </div>
      </div>

    </div>
  </header><!-- End Header -->

  <!-- ======= Hero Section ======= -->
  <section id="hero">
    <div class="hero-container">
      <div id="heroCarousel" class="carousel slide carousel-fade" data-ride="carousel">
        <ol class="carousel-indicators" id="hero-carousel-indicators"></ol>
        <div class="carousel-inner" role="listbox">

          <div class="carousel-item active" v-bind:style='{ backgroundImage: `url("${heroimg[0].url}")` }' >
            <div class="carousel-background"><img src="" alt=""></div>
            <div class="carousel-container">
              <div class="carousel-content">
                <div class="row">
                  <div class="col-lg-8">
                  <h2 class="animate__animated animate__fadeInDown"><span>CARE & COMFORT</span> Disability Service Provider </h2>
                <!--  <h4 class="animate__animated animate__fadeInUp">Group Company of <a href="http://gaurservices.com/">GISPL</a></h4> -->
                                  <div>
                  <a href="#cta"
                      class="btn-menu animate__animated animate__fadeInUp scrollto">Community Nursing</a>
                  <a href="#personal-care"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Personal Care  </a>
                  <a href="#home-care-services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Home Care Services
                  </a>
                  <a href="#comminity-access"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Community access
                  </a>
                  <a href="#support-coodination"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Support Coordination
                  </a>

                </div>
                  </div>
                  <div class="col-lg-4 d-flex align-items-center justify-content-center" data-aos="zoom-in" data-aos-delay="200">
                       <!-- <a href="https://www.youtube.com/watch?v=TTsfAlf2LnY" class="venobox play-btn" data-vbtype="video" data-autoplay="true"></a> -->
                  </div>
                </div>
                </div>
            </div>
          </div>
          <div class="carousel-item" v-bind:style='{ backgroundImage: `url("${heroimg[1].url}")` }'>
          <div class="carousel-background"><img src="" alt=""></div>
             <div class="carousel-container">
              <div class="carousel-content">
                <div class="row">
                  <div class="col-lg-8">
                 <h2 class="animate__animated animate__fadeInDown"><span>CARE AND COMFORT</span> Disability Service Provider </h2>
                <div>
                  <a href="#cta"
                      class="btn-menu animate__animated animate__fadeInUp scrollto">Community Nursing</a>
                  <a href="#security"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Personal Care  </a>
                  <a href="#manpower"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Home Care Services
                  </a>
                  <a href="#manpower"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Community access
                  </a>
                  <a href="#manpower"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Support Coordination
                  </a>

                </div>
                  </div>
                  <div class="col-lg-4 d-flex align-items-center justify-content-center" data-aos="zoom-in" data-aos-delay="200">
                       <!-- <a href="https://www.youtube.com/watch?v=TTsfAlf2LnY" class="venobox play-btn" data-vbtype="video" data-autoplay="true"></a> -->
                  </div>
                </div>
                </div>
            </div>
          </div>
          <div class="carousel-item" v-bind:style='{ backgroundImage: `url("${heroimg[2].url}")` }'>
            <div class="carousel-background"><img src="" alt=""></div>
            <div class="carousel-container">
              <div class="carousel-content">
                  <h2 class="animate__animated animate__fadeInDown"><span>CARE AND COMFORT</span> Disability Service Provider </h2>
                    <div>
                  <a href="#cta"
                      class="btn-menu animate__animated animate__fadeInUp scrollto">Community Nursing</a>
                  <a href="#security"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Personal Care  </a>
                  <a href="#manpower"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Home Care Services
                  </a>
                  <a href="#manpower"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Community access
                  </a>
                  <a href="#manpower"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Support Coordination
                  </a>

                </div>
              </div>
            </div>
          </div>
        </div>

        <a class="carousel-control-prev" href="#heroCarousel" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon icofont-simple-left" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>

        <a class="carousel-control-next" href="#heroCarousel" role="button" data-slide="next">
          <span class="carousel-control-next-icon icofont-simple-right" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>

      </div>
    </div>
  </section>


  <main id="main">

    <!-- ======= About Us Section ======= -->
    <section id="about" class="about">
      <div class="container" data-aos="fade-up">

        <div class="section-title">
          <h2>About Us</h2>
          <p>CARE AND COMFORT, is a disability service provider company, founded by two very passionate and enthusiastic nurses, who have been in the health and service Industry for more than 30 years combined.

           The Enthusiasm to care and look after our community in need with compassion and Respect has grown stronger and stronger over the years. To serve better, we as health care providers wanted to extend our horizon and spread our wings, and bring our specialised skills to the community.</p>
        </div>

        <div class="row content">
          <div class="col-lg-6">
            <p>

           Two highly competent and compassionate Nurses with a wealth of clinical Experience.
            Ganga is currently working as a hospital case manager and this role has commissioned
            her to liaise and coordinate with community stakeholders. It has allowed her to work
            collaboratively with social workers, physicians, allied health team, clients and their
            families and community case managers. She has experience in acute clinical areas such as
            ICU, Emergency Departments and Cardiac Units for more than 20 years.
             She also has post graduate Certification in Critical care Nursing.
            </p>
              <div class="section-title">
          <h2>Our Values</h2>
          <p></p>
        </div>
            <ul>
              <li><i class="ri-check-double-line"></i> Respect</li>
              <li><i class="ri-check-double-line"></i> Equanimity</li>
              <li><i class="ri-check-double-line"></i> Compassion</li>
               <li><i class="ri-check-double-line"></i> Excellence</li>
            </ul>
          </div>
          <div class="col-lg-6 pt-4 pt-lg-0">
            <p>
             Dena on the other hand brings her extensive Cardiology nursing experience well over 10 years, and holds a Graduate diploma in Advanced Nursing. They both have current Basic Life support and Advanced Life Support Certificates.

The health care Industry is something they have dived into over decades. You can trust us and stay assured that you or your loved ones are in very safe and capable hands. It is our promise to provide exceptional and Quality care that  you truly deserve .


            </p>
         <!--   <a href="http://gaurservices.com/" class="btn-learn-more">Learn More</a>   -->
          </div>
        </div>

      </div>
    </section><!-- End About Us Section -->

    <!-- ======= Services Section ======= -->
    <section id="services" class="services">
      <div class="container" data-aos="fade-up">

        <div class="section-title">
          <h2>Services</h2>
          <p></p>
        </div>

        <div class="row">
          <div class="col-lg-4 col-md-2 d-flex align-items-stretch">
            <div class="icon-box">
              <div class="icon"><i class="bx bxl-dribbble"></i></div>
              <h4><a href="">Community Nursing</a></h4>
              <p> Medication Administration, Continence Management, Wound Management</p>
            </div>
          </div>

          <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-md-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-file"></i></div>
              <h4><a href="">Personal Care</a></h4>
 <p> Assisting with activities of daily Living, such as Showering, toileting, and Grooming.</p>
            </div>
          </div>

          <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-lg-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-tachometer"></i></div>
              <h4><a href="">Home Care Services</a></h4>
 <p>Domestic Cleaning, meal preparation, Laundry, pet care and Gardening.</p>
            </div>
          </div>


           <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-lg-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-tachometer"></i></div>
              <h4><a href="">Community access</a></h4>
 <p> Social, Community and Recreational participation and Transportation.</p>
            </div>
          </div>
           <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-lg-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-tachometer"></i></div>
              <h4><a href="">Support Coordination</a></h4>

            </div>
          </div>

        </div>

      </div>
    </section><!-- End Services Section -->



    <section id="contact" class="contact">
      <div class="container" data-aos="fade-up">
        <div class="section-title"><h2>Contact</h2><!--<p>Contact Us</p>-->
        </div>
        <p> We are in the south eastern and Eastern suburbs of Melbourne primarily but we are keen to travel and serve you as needed. Distance is just an excuse otherwise.</p>
      </div>

      <div class="container" data-aos="fade-up">

            <div class="info ">
              <div class="row mt-2 mb-5">
          <div class="col-lg-4 col-md-6">
              <span class="address">
                <i class="icofont-google-map"></i>
                <h4>Location:</h4><p>Ringwood<br> VIC - 3134</p>
              </span>
          </div>

          <div class="col-lg-4 col-md-6">
              <span class="phone"><i class="icofont-phone"></i><h4>Call:</h4>
                  <p>(+61) 0493 177 074</p>
                  <p>(+61) 0493 171 266</p>
              </span>
          </div>
          <div class="col-lg-4 col-md-6">

              <span class="email"><i class="icofont-envelope"></i>
                <h4>Email:</h4>
                <p>info@careandcomfort.net.au</p>
                <p>ganga.selvaraj126@gmail.com</p>
              </span>
            </div>
          </div>
        </div>
      </div>
      <div data-aos="fade-up">
        <!--<iframe style="border:0; width: 100%; height: 350px;" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d12097.433213460943!2d-74.0062269!3d40.7101282!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb89d1fe6bc499443!2sDowntown+Conference+Center!5e0!3m2!1smk!2sbg!4v1539943755621" frameborder="0" allowfullscreen></iframe> -->
        <iframe style="border:0; width: 100%; height: 350px;" src="https://www.google.com/maps/embed/v1/place?q=Ringwood+VIC,+Australia&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8" width="600" height="450" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
    </section><!-- End Contact Section -->
  </main><!-- End #main -->

  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <h3>CARE & COMFORT </h3>
      <p>Disability Service Provider </p>
      <div class="social-links">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="google-plus"><i class="bx bxl-skype"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
      <div class="copyright">
        &copy; Copyright <strong><span>CARE & COMFORT Disability Service Provider</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        <!-- All the links in the footer should remain intact. -->
        <!-- You can delete the links only if you purchased the pro version. -->
        <!-- Licensing information: https://bootstrapmade.com/license/ -->
        <!-- Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/knight-simple-one-page-bootstrap-template/ -->
        Designed by <a href="https://www.manojkmishra.com/">MKM</a>
      </div>
    </div>
  </footer><!-- End Footer -->

  <!--<div id="preloader"></div>-->
  <a href="#" class="back-to-top"><i class="ri-arrow-up-line"></i></a>

  <!-- Vendor JS Files -->
 <!-- <script src="../assets/vendor/jquery/jquery.min.js"></script>
  <script src="../assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="../assets/vendor/jquery.easing/jquery.easing.min.js"></script>
  <script src="../assets/vendor/php-email-form/validate.js"></script>
  <script src="../assets/vendor/waypoints/jquery.waypoints.min.js"></script>
  <script src="../assets/vendor/counterup/counterup.min.js"></script>
  <script src="../assets/vendor/isotope-layout/isotope.pkgd.min.js"></script>
  <script src="../assets/vendor/venobox/venobox.min.js"></script>
  <script src="../assets/vendor/owl.carousel/owl.carousel.min.js"></script> -->

  <!-- Template Main JS File -->
 <!-- <script src="../assets/js/main.js"></script> -->

</div>

</template>

<script>
export default {
  data(){
    return {
      venoimg:[//{url:`${require(`~/assets/img/gallery/gallery-1.jpg`)}`},
                      //{url:`${require(`~/assets/img/gallery/gallery-2.jpg`)}`},
                      {url:`${require(`~/assets/img/gallery/gal6.jpg`)}`},
                      {url:`${require(`~/assets/img/gallery/gal8.jpg`)}`},
                      {url:`${require(`~/assets/img/gallery/gal1.jpg`)}`},
                      {url:`${require(`~/assets/img/gallery/gal2.jpg`)}`},
                      {url:`${require(`~/assets/img/gallery/gal333.jpg`)}`},
                      {url:`${require(`~/assets/img/gallery/gal4.jpg`)}`},
                      {url:`${require(`~/assets/img/gallery/gal5.jpg`)}`},

                      {url:`${require(`~/assets/img/gallery/gal7.jpg`)}`},
                      //{url:`${require(`~/assets/img/gallery/awards.jpg`)}`},

                    ],
                                  heroimg:[//{url:`${require(`~/assets/img/slide/slide-1.jpg`)}`},
                                   {url:`${require(`~/assets/img/cnc/Disability.News.png`)}`},
                    {url:`${require(`~/assets/img/cnc/image1.png`)}`},
                      //{url:`${require(`~/assets/img/slide/slide-2.jpg`)}`},
                      {url:`${require(`~/assets/img/cnc/image3.webp`)}`},

                      {url:`${require(`~/assets/img/slide/slide-3.jpg`)}`},
                      {url:`${require(`~/assets/img/slide/slide-3.jpg`)}`},
                      {url:`${require(`~/assets/img/slide/slide-3.jpg`)}`},
                    ]
    }
},
mounted(){
  this.aos_init();
    $('.venobox').venobox();
    //-----------------------------hero ----------------
      if (window.matchMedia("(max-width: 767px)").matches) {
    $('#hero').css({
      height: $(window).height()
    });
  }

  // Intro carousel
  var heroCarousel = $("#heroCarousel");
  var heroCarouselIndicators = $("#hero-carousel-indicators");
  heroCarousel.find(".carousel-inner").children(".carousel-item").each(function(index) {
    (index === 0) ?
    heroCarouselIndicators.append("<li data-target='#heroCarousel' data-slide-to='" + index + "' class='active'></li>"):
      heroCarouselIndicators.append("<li data-target='#heroCarousel' data-slide-to='" + index + "'></li>");
  });

  heroCarousel.on('slid.bs.carousel', function(e) {
    $(this).find('h2').addClass('animate__animated animate__fadeInDown');
    $(this).find('p, .btn-menu, .btn-book').addClass('animate__animated animate__fadeInUp');
  });
    //-------------------scroll navbar up after some height---
      $(window).scroll(function()
      {    if ($(this).scrollTop() > 100) {
            $('#header').addClass('header-scrolled');
            $('#topbar').addClass('topbar-scrolled');
            } else {
              $('#header').removeClass('header-scrolled');
              $('#topbar').removeClass('topbar-scrolled');
            }
      });

    if ($(window).scrollTop() > 100)
      {
        $('#header').addClass('header-scrolled');
        $('#topbar').addClass('topbar-scrolled');
      }
      //--------------------------------
    this.$nextTick(function ()
    {
    // Code that will run only after the
    // entire view has been rendered
    //--------------------------------------------------------------
    var scrolltoOffset = $('#header').outerHeight() - 1;
      $(document).on('click', '.nav-menu a, .mobile-nav a, .scrollto',
      function(e) //on click --> go to menu place
      {  if (location.pathname.replace(/^\//, '') == this.pathname.replace(/^\//, '') && location.hostname == this.hostname)
        {
          var target = $(this.hash);
          console.log('scroll target-',target,'offset',scrolltoOffset)
          if (target.length)
          { e.preventDefault();
            var scrollto = target.offset().top - scrolltoOffset;
            console.log('scroll target1-',scrollto)
            if ($(this).attr("href") == '#header')
            { scrollto = 0; console.log('scrolled to header')  }
            $('html, body').animate({ scrollTop: scrollto }, 500, 'easeInOutExpo');
//--------------------------mobile-----------------------------------------
            if ($(this).parents('.nav-menu, .mobile-nav').length)
            {
              console.log('hehe1')
              $('.nav-menu .active, .mobile-nav .active').removeClass('active');
              $(this).closest('li').addClass('active');
            }
            if ($('body').hasClass('mobile-nav-active'))
            { $('body').removeClass('mobile-nav-active');
              $('.mobile-nav-overly').fadeOut();
            }
//-------------------------mobile finish------------------
            return false;
          }
          //====================

        }
      });
      // Navigation active state on scroll------------------
      var nav_sections = $('section');
      var main_nav = $('.nav-menu, .mobile-nav');
//------------------------------------only for shwoing menu amber color when selected----------------
      $(window).on('scroll', function()
      {  var cur_pos = $(this).scrollTop() + 200;
        nav_sections.each(function()
        { var top = $(this).offset().top,
          bottom = top + $(this).outerHeight();
          if (cur_pos >= top && cur_pos <= bottom)
          {  if (cur_pos <= bottom) {  main_nav.find('li').removeClass('active');   }
            main_nav.find('a[href="#' + $(this).attr('id') + '"]').parent('li').addClass('active');
          }
          if (cur_pos < 300) {  $(".nav-menu ul:first li:first").addClass('active'); }
        });
      });
          /*  if (window.location.hash)
            {
          var initial_nav = window.location.hash;
          if ($(initial_nav).length) {
            var scrollto = $(initial_nav).offset().top - scrolltoOffset;
            $('html, body').animate({
              scrollTop: scrollto
            }, 1500, 'easeInOutExpo');
          }
        }*/
        //-----------------------------
          // Back to top button----------------------------
  $(window).scroll(function() {
    if ($(this).scrollTop() > 100) {
      $('.back-to-top').fadeIn('slow');
    } else {
      $('.back-to-top').fadeOut('slow');
    }
  });

  $('.back-to-top').click(function() {
    $('html, body').animate({
      scrollTop: 0
    }, 1500, 'easeInOutExpo');
    return false;
  });
  //-----------------------------------scroll to top finish---isotope
    // food Menu list isotope and filter
 /* $(window).on('load', function()
  {console.log('menu filter----1')
    var menuIsotope = $('.menu-container').isotope({
      itemSelector: '.menu-item',
      layoutMode: 'fitRows'
    });

    $('#menu-flters li').on('click', function() {
      console.log('menu filter----2')
      $("#menu-flters li").removeClass('filter-active');
      $(this).addClass('filter-active');

      menuIsotope.isotope({ filter: $(this).data('filter') });
     // aos_init();
    });
  });*/
  //----------------------------

    })//next tick finish


  $(".events-carousel").owlCarousel({ autoplay: true,  dots: true, loop: true, items: 1 });

  // Testimonials carousel (uses the Owl Carousel library)
  $(".testimonials-carousel").owlCarousel({
    autoplay: true, dots: true, loop: true, autoplayTimeout: 6000,
    responsive: { 0: { items: 1 }, 768: { items: 2 }, 900: { items: 3 } }
  });
  //-----------------------------
    // Mobile Navigation
  if ($('.nav-menu').length)
  {  var $mobile_nav = $('.nav-menu').clone().prop({  class: 'mobile-nav d-lg-none' });
    $('body').append($mobile_nav);
    $('.mobile-nav').prepend('<button type="button" class="mobile-nav-close"><i class="icofont-close"></i></button>');
    $('#header').append('<button type="button" class="mobile-nav-toggle d-lg-none"><i class="icofont-navigation-menu"></i></button>');
    $('body').append('<div class="mobile-nav-overly"></div>');

    $(document).on('click', '.mobile-nav-toggle', function(e) {
      $('body').toggleClass('mobile-nav-active');
      $('.mobile-nav-overly').toggle();
    });

    $(document).on('click', '.mobile-nav-close', function(e) {
      $('body').removeClass('mobile-nav-active');
      $('.mobile-nav-overly').fadeOut();
    });

    $(document).on('click', '.mobile-nav .drop-down > a', function(e) {
      e.preventDefault();
      $(this).next().slideToggle(300);
      $(this).parent().toggleClass('active');
    });

    $(document).click(function(e) {
      var container = $(".mobile-nav, .mobile-nav-toggle");
      if (!container.is(e.target) && container.has(e.target).length === 0) {
        if ($('body').hasClass('mobile-nav-active')) {
          $('body').removeClass('mobile-nav-active');
          $('.mobile-nav-toggle i').toggleClass('icofont-navigation-menu icofont-close');
          $('.mobile-nav-overly').fadeOut();
        }
      }
    });
  } else if ($(".mobile-nav, .mobile-nav-toggle").length)
  {  $(".mobile-nav, .mobile-nav-toggle").hide();
  }
//------------------------mobile nav finish

},
  methods:{
    aos_init() {  AOS.init({duration: 1000, once: true });  }
  }
}
</script>

<style>

</style>
