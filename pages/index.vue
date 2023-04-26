<template>
  <div>

  <!-- ======= Header ======= -->
  <header id="header" class="fixed-top ">
    <div class="container-fluid">

      <div class="row justify-content-center">
        <div class="col-xl-9 d-flex align-items-center justify-content-between">
        <h1 class="logo"><a href="/"><span>CURE N CARE Physiotherapy</span></a></h1> 
           <h1 class="logo mr-auto"><nuxt-link  :to="{ path: '/'}">
     <!--<span><img src="../assets/img/cnc/cnc_logo2.png" class="logo-img" alt=""></span>--> 
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
                  <h2 class="animate__animated animate__fadeInDown"><span>CURE N CARE</span> Physiotherapy</h2>
                <!--  <h4 class="animate__animated animate__fadeInUp">Group Company of <a href="http://gaurservices.com/">GISPL</a></h4> -->
                                  <div>
                  <a href="#services"
                      class="btn-menu animate__animated animate__fadeInUp scrollto">Physiotherapy</a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Kids Physiotherapy</a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Musculoskeletal Physiotherapy

                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Sports Injury & Rehabilitation
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Hydrotherapy Consultation
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Women's Health
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Dry Needling
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Exercise & Rehabilitation
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
                 <h2 class="animate__animated animate__fadeInDown"><span>CURE N CARE</span> Physiotherapy </h2>
                 <div>
                  <a href="#services"
                      class="btn-menu animate__animated animate__fadeInUp scrollto">Physiotherapy</a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Kids Physiotherapy</a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Musculoskeletal Physiotherapy

                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Sports Injury & Rehabilitation
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Hydrotherapy Consultation
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Women's Health
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Dry Needling
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Exercise & Rehabilitation
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
                  <h2 class="animate__animated animate__fadeInDown"><span>CURE N CARE</span> Physiotherapy </h2>
                  <div>
                  <a href="#services"
                      class="btn-menu animate__animated animate__fadeInUp scrollto">Physiotherapy</a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Kids Physiotherapy</a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Musculoskeletal Physiotherapy

                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Sports Injury & Rehabilitation
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Hydrotherapy Consultation
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Women's Health
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Dry Needling
                  </a>
                  <a href="#services"
                      class="btn-book animate__animated animate__fadeInUp scrollto mt-1">Exercise & Rehabilitation
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
          <p>Cure n Care is a provider of high-quality physiotherapy in the Frankston and surrounding area for over 10 years. We are dedicated to managing your health and well-being through qualified assessment, diagnosis and treatment to achieve your specific goals. Shared decision making, whereby you are involved in shaping the course of your treatment and type of treatment you receive, is core to our practice. 
We strive to provide exceptional physiotherapy using the latest evidence based physiotherapy with the latest in skills to ensure the recover of your health.</p>
        </div>

        <div class="row content">
          <div class="col-lg-6">
            <p>           
<strong>Qualification:</strong><br>
Yamini Sethi graduated from Karnataka University (Bangalore), India in 2009 specializing in Orthopedic division of Physiotherapy with highest distinction. She migrated to Australia in 2012 and started practicing Physiotherapy in 2014. She registered with Australian Health Practitioner Regulation Agency (Ahpra) in 2016 and has been practicing as a Physiotherapist since then.

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
<strong>Experience:</strong><br>
She has gained many years of valuable experience by working in various settings including Private practice, Aged Care Homes, In-Community Physio services. She has worked in various settings including Outpatient clinics, Rehab Centres, Acute and Post Acute/Rehab Hospitals, Spinal Cord injuries treatment, Home Care. Since graduation, Yamini continued to demonstrate keen interest in Orthopedic and Post Surgical Rehab, She is also very keen in treating women’s health issues/pelvic floor physiotherapy. She combines various treatment techniques and methodologies including manual therapy, exercise therapy, modalities and dry needling.
            </p>
            <p>           
<strong>Passion:</strong><br>


Yamini is a passionate physiotherapist with keen interest in all areas of musculoskeletal and women’s health physiotherapy. She uses a diverse range of treatment techniques including manual therapy techniques, soft tissue mobilisation, dry needling, developing personalised exercise programs to assist her patients reach their optimum health goals. I have good results in treating pelvic girdle and hip pain, back pain, neck pain and headaches. 

The key motivator for me is the health of my clients. I enjoy developing a great rapport with my clients and getting them back in form.

            </p>
         <!--   <a href="http://gaurservices.com/" class="btn-learn-more">Learn More</a>   -->
          </div>
        </div>

      </div>
    </section><!-- End About Us Section -->



    <section id="security" class="cta security">
      <div class="container" data-aos="fade-up">

        <div class="row">
          <div class="col-lg-9 text-center text-lg-left">
            <h3>Our Services</h3>
            <p> View our wide range of services to help you get moving again </p>
          </div>
          <div class="col-lg-3 cta-btn-container text-center">
            <a class="cta-btn align-middle" href="#contact">Contact Us</a>
          </div>
        </div>

      </div>
    </section><!-- End Cta Section -->
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
              <h4><a href="">Physiotherapy</a></h4>
              <ul> 

<li>Joint mobilizations</li>
<li>Taping and bracing</li>
<li>Trigger point therapy</li>
<li>Massage areas of your body (Soft tissue release)</li>
<li>Stretch your muscles</li>
<li>Exercises to strengthen your muscles</li>
              </ul>
            </div>
          </div>

          <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-md-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-file"></i></div>
              <h4><a href="">Kids Physiotherapy</a></h4>
              <h5>Kids & Teen well-being</h5>
              <ul> 

<li>Learn how to report pain</li>
<li>Differentiate different types of pain/sensations</li>
<li>Make them feel comfortable in our space</li>
<li>Empower them in taking charge of their own bodies</li>
<li>Manual rehab, exercise treatment, movement based approach</li>

              </ul>
            </div>
          </div>

          <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-lg-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-tachometer"></i></div>
              <h4><a href="">Musculoskeletal Physiotherapy</a></h4>
              <h5>Geriatric Physiotherapy</h5>
              <ul> 

<li>Arthritis and Osteoarthritis</li>
<li>Maintaining mobility</li>
<li>Building strength</li>
<li>Accident & fall prevention</li>
<li>Rehabilitation post accident or operation</li>
<li>Exercise & rehab before operation</li>

              </ul>
            </div>
          </div>


           <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-lg-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-tachometer"></i></div>
              <h4><a href="">Sports Injury & Rehabilitation</a></h4>
              <ul> 

<li>Joint sprains, Muscle strains</li>
<li>Overuse injuries e.g. achilles ‘tendonitis’, tennis elbow etc.</li>
<li>Common and complex lumbo-pelvic dysfunction e.g. Pelvic Instability, Osteitis Pubis (‘OP’)</li>
<li>Injury prevention</li>
<li>Performance Enhancement</li>
<li>Acute Intervention</li>

              </ul>
            </div>
          </div>

           <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-lg-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-tachometer"></i></div>
              <h4><a href="">Hydrotherapy Consultation</a></h4>
              <ul> 

<li>Relieve muscle tension</li>
<li>Relieve chronic pain due to injury or arthritis</li>
<li>Balance & stability issues</li>


              </ul>
            </div>
          </div>

          <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-lg-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-tachometer"></i></div>
              <h4><a href="">Women's Health</a></h4>
              <h5>Women's Health & Continence Physio</h5>
              <ul> 

<li>Pelvic health</li>
<li>Pregnancy and Postnatal treatment</li>
<li>Treating women for back pain and pelvic pain during pregnancy</li>
<li>Stress and urge incontinence</li>
<li>Prolapse</li>
<li>Incontinence or leakage of the bladder or bowel</li>

              </ul>
            </div>
          </div>

          <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-lg-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-tachometer"></i></div>
              <h4><a href="">Dry Needling</a></h4>
              <ul> 

<li>Promote localized inflammatory response</li>
<li>Relieve joint pain & dysfunction</li>
<li>Improve muscle activation</li>
<li>Decrease muscular tightness & strengthen muscular contraction</li>
<li>Promote new healing</li>
<li>Eliminate myofascial trigger points</li>

              </ul>
            </div>
          </div>

          <div class="col-lg-4 col-md-2 d-flex align-items-stretch mt-4 mt-lg-0">
            <div class="icon-box">
              <div class="icon"><i class="bx bx-tachometer"></i></div>
              <h4><a href="">Exercise & Rehabilitation</a></h4>
              <ul> 

<li>Focus on developing strength</li>
<li>Step-by-step programming to safely achieve full recovery</li>
<li>Retraining for both dynamic or static activities or sports to ensure correct technique</li>
<li>Systematic assessment and treatment of the muscles, tendons, ligaments and connective tissues</li>

              </ul>
            </div>
          </div>

        </div>

      </div>
    </section><!-- End Services Section--------------------------------- -->
    <section id="security" class="cta security">
      <div class="container" data-aos="fade-up">

        <div class="row">
          <div class="col-lg-9 text-center text-lg-left">
            <h3>Why choose us?</h3>
            <p> Our purpose built facility offers you comfort with quality care using some of the most advanced physiotherapy equipment available. </p>
          </div>
          <div class="col-lg-3 cta-btn-container text-center">
            <a class="cta-btn align-middle" href="#contact">Contact Us</a>
          </div>
        </div>

      </div>
    </section><!-- End Cta Section -->

    <!-- ======= Features Section ======= -->
    <section id="features" class="features">
      <div class="container" data-aos="fade-up">

        <div class="row">
          <div class="col-lg-6 order-2 order-lg-1">
            <div class="icon-box mt-5 mt-lg-0">
              <i class="bx bx-receipt"></i>
              <h4>Hands-On Treatment</h4>
              <p>At Cure n Care we are driven to achieve the best standard of clinical care and quality patient outcomes.
Our key point of difference is the value we place on high-level physical rehabilitation.<br/><br/>
<strong>Manual physiotherapy</strong> (hands on treatment) plays a crucial role in your recovery. It can be critical to help restore normal movement, regain high-level function, and resolve pain, stiffness or tightness.
              </p>
            </div>
            <div class="icon-box mt-5">
              <i class="bx bx-cube-alt"></i>
              <h4>Personalized Care</h4>
              <p>

Our Physiotherapists will perform a thorough initial assessment followed by a personalized rehabilitation plan. At Cure n Care Physiotherapy are amazing Physio’s work with you to find the root cause of your problem and create personalized rehabilitation plan based on your specific need to works towards your recovery goals. We take time to listen to your problems and health concerns. We treat you as a person and not just a client/number.
<br/><br/>
We provide evidence based, client-centred care.
<br/><br/>
We provide treatment based on research and scientific evidence in a friendly, welcoming and professional environment. We treat holistically, and reckon rehabilitation to be more than just pain resolution; the ultimate goal is to have a better quality of life going forward.
</p>
            </div>
            <div class="icon-box mt-5">
              <i class="bx bx-images"></i>
              <h4>Education & Awareness</h4>
              <p>

We discover and treat the source/root of your problem. We educate you fully to understand your injury and pain, so you can efficiently recover. Many times, the spot that hurts you is not the actual origin of the problem. Finding and treating the real source not only helps in curing the problem but also reduces the risk of recurring problems and slower recovery.
<br/><br/>
We engage in ongoing professional education.
<br/><br/>
We regularly attend courses and conferences to keep our skills and knowledge up-to-date with current research. This empower us to use new research findings and clinical skills into our treatment plans, and provide the best quality of care.
</p>
            </div>
            <div class="icon-box mt-5">
              <i class="bx bx-shield"></i>
              <h4>Preventative Approach</h4>
              <p>

Injury Prevention and Rehabilitation
<br/><br/>
We take proactive approach in preventing pain and injury before they occur by using preventive analysis and providing treatment to normalise our patients’ movement patterns that cause injuries from occurring – or re-occurring.
</p>
            </div>
            <div class="icon-box mt-5">
              <i class="bx bx-shield"></i>
              <h4>Nurturing Relationship</h4>
              <p>

We believe strongly in a relaxing and friendly clinical environment.
<br/><br/>
We believe that a successful Physiotherapist – client relationship is client centred and is based on effective communication, good listening skills, empathy and trust. We believe in taking time and effort to educate you about your problem and what needs to be done about it. It’s not about what we can do for you but also about engaging and empowering you.
<br/><br/>
A careful combination of Manual Therapy and active Rehabilitation is the formula for your success.</p>
            </div>
          </div>
          <div class="image col-lg-6 order-1 order-lg-2" style='background-image: url("../assets/img/features.jpg");'></div>
        </div>

      </div>
    </section><!-- End Features Section -->


    <section id="contact" class="contact">



      <div class="container" data-aos="fade-up">

        <div class="section-title"><h2>Contact</h2><!--<p>Contact Us</p>-->
        </div>
       
      </div>

      <div class="container" data-aos="fade-up">

            <div class="info ">
              <div class="row mt-2 mb-5">
          <div class="col-lg-4 col-md-6">
              <span class="address">
                <i class="icofont-google-map"></i>
                <h4>Location:</h4><p>2 Finlay St, Frankston<br> VIC - 3199</p>
              </span>
          </div>

          <div class="col-lg-4 col-md-6">
              <span class="phone"><i class="icofont-phone"></i><h4>Call:</h4>
                  <p>(03) 9088 4100</p>
              </span>
          </div>
          <div class="col-lg-4 col-md-6">

              <span class="email"><i class="icofont-envelope"></i>
                <h4>Email:</h4>
                <p>admin@curencarephysio.com.au</p>
              </span>
            </div>
          </div>
        </div>
        
      </div>
      <div data-aos="fade-up">
        <!--<iframe style="border:0; width: 100%; height: 350px;" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d12097.433213460943!2d-74.0062269!3d40.7101282!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb89d1fe6bc499443!2sDowntown+Conference+Center!5e0!3m2!1smk!2sbg!4v1539943755621" frameborder="0" allowfullscreen></iframe> -->
        <iframe style="border:0; width: 100%; height: 350px;" src="https://www.google.com/maps/embed/v1/place?q=2+Finlay+St,+Frankston&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8" width="600" height="450" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
     
         
    </section><!-- End Contact Section -->
    <div class="container" data-aos="fade-up">

<div class="section-title"><h2>What to expect at Cure n Care</h2><!--<p>Contact Us</p>-->

     
          <p></p>
        </div>
            <ul>
              <li><i class="ri-check-double-line"></i> Convenient Location </li>
              <li><i class="ri-check-double-line"></i> Ample free parking </li>
              <li><i class="ri-check-double-line"></i> Ground floor clinic </li>
               <li><i class="ri-check-double-line"></i> No referral required </li>
               <li><i class="ri-check-double-line"></i> Private treatment room  </li>
               <li><i class="ri-check-double-line"></i> Treatment for men, women, children of all ages  </li>
               <li><i class="ri-check-double-line"></i> One-to-one treatment  </li>
            </ul>


</div>
<br/><br/>
  </main><!-- End #main -->

  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <h3>CURE N CARE </h3>
      <p>Physiotherapy</p>
      <div class="social-links">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="google-plus"><i class="bx bxl-skype"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
      <div class="copyright">
        &copy; Copyright <strong><span>CURE N CARE Physiotherapy</span></strong>. All Rights Reserved
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
