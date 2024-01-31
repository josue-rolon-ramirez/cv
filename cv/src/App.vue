<template>
  <div class="container mw-100" >
    <div class="row">
      <div class="col-12 gx-0" id="bgfondo" >
        
      </div>
      <div class="col-lg-6 col-md-12 col-sm-12  position-absolute photo-profile-content gx-0">
          <img src="../src/img/profile-photo.jpg" alt="" class="photo-profile">
        </div>

        <div class="col-lg-6 col-md-12 col-sm-12 position-absolute content-text">
       <h2 class="illuminated-text"> Josué Rolón Ramírez <br>Desarrollador & Diseñador web</h2>  
      
      </div>

      
      </div>

      <div class="row text-center" >
        <h3 class="lineUp">Conocimientos</h3>
      </div>


      <div class="row swiper-content mx-auto">
        
        <div class="col-12 mb-10">
        <swiper
    :slidesPerView="3"
    :spaceBetween="60"
    :pagination="{
      clickable: true,
    }"
    :modules="modules"
    class="mySwiper"
  >
    <swiper-slide><img src="./img/html-logo.png" alt="html-image"></swiper-slide>
    <swiper-slide ><img src="./img/css-logo.png" alt="css-image"></swiper-slide>
    <swiper-slide><img src="./img/js-logo.png" alt="js-image"></swiper-slide>
    <swiper-slide><img src="./img/php-logo.png" alt="php-image"></swiper-slide>
    <swiper-slide><img src="./img/bootstrap-logo.png" alt="bootstrap-image"></swiper-slide>
    <swiper-slide><img src="./img/wordpress-logo.png" alt="wordpress-image"></swiper-slide>
    <swiper-slide><img src="./img/vue-logo.png" alt="vue-image"></swiper-slide>
    <swiper-slide><img src="./img/figma-logo.png" alt="figma-image"></swiper-slide>
  </swiper>

        </div>
     </div>
      
     <div class="row text-center ">
        <div class="col-lg-6 col-md-12">
          <h3 class="lineUp">Proyectos Web</h3>
          <h4 class="st-h4">Diseño,desarrollo y estilos con:</h4>

          <div class="d-lg-flex justify-content-around mt-5">

            <div class="card col-lg-3 col-md-6  d-md-block col-sm-6 mb-md-5 mx-auto d-sm-block mb-sm-5 col-6 mb-5"><a href="https://nicksanmexico.com/" target="_blank"><img class="w-100" src="./img/nicksan-page-img.jpg" alt="nicksan"></a>
              <h4 class="mt-3 mb-4">Nicksan</h4>
             
            <ul class="mx-auto card-content">
            <li class="card-text">CMS Wordpress</li>
            <li class="card-text">Html</li>
            <li class="card-text">Css</li>
            <li class="card-text">Figma</li>
          </ul>
        
          </div>
          
          <div class="card col-lg-3 col-md-6 d-md-block col-sm-6 mb-md-5 mx-auto d-sm-block mb-sm-5 col-6 mb-5"><a href="https://dstockgourmet.com" target="_blank"><img class="w-100" src="./img/dstock-page-img.png" alt="dstock"></a>
            <h4 class="mt-3 mb-4">Dstockgourmet</h4>
            <ul class="mx-auto card-content">
            <li class="card-text">CMS Wordpress</li>
            <li class="card-text">Html</li>
            <li class="card-text">Css</li>
            <li class="card-text">Figma</li>
            <p class="detail card-content">(Proyecto retirado por empresa)</p>
          </ul>
          </div>
          
          <div class="card col-lg-3 col-md-6 d-md-block  col-sm-6 mb-md-5 mx-auto d-sm-block mb-sm-5 col-6 mb-5"><a href="../crud-usuarios/login.php" target="_blank"><img class="w-100" src="./img/crud-usuarios-img.jpg" alt="crud-usuarios"></a>
            <h4 class="mt-3 mb-4">Crud de usuarios</h4>
            <ul class="mx-auto card-content">
            <li class="card-text">Html</li>
            <li class="card-text">Css</li>
            <li class="card-text">Php</li>
            <li class="card-text">Bootstrap</li>
          </ul>
          </div>
        
        </div>
        </div>

        <div class="col-lg-6 col-md-12">
          <h3 class="lineUp">Diseños Web</h3>
          <h4 class="st-h4">Diseñados en Figma</h4>

          <div class="d-lg-flex d-md-flex d-sm-flex justify-content-around mt-5">
            
            <div class="card col-md-3 col-sm-3 col-6 mb-5 mx-auto"><a href="https://www.figma.com/file/99oUUfgYUURyjBYZLivdRP/Dise%C3%B1o-Avanzado-Nicksan-(mobile)?type=design&node-id=0%3A1&mode=design&t=uvKTq5uddSlYEMZa-1" target="_blank"><img class="w-100" src="./img/figma-nicksan-img.jpg" alt="nicksan"></a>
              <h4 class="mt-3 mb-3">Nicksan - Mobile</h4>
            </div>
            
            <div class="card col-md-3 col-sm-3 col-6 mb-5 mx-auto"><a href="https://www.figma.com/file/OLak3dJ2K1xI90QHiD7UYk/Dstock-wireframe-(mobile)?type=design&node-id=0%3A1&mode=design&t=01KBxyAgS2D4iKlP-1" target="_blank"><img class="w-100" src="./img/figma-dstock-img.jpg" alt="dstock"></a>
              <h4 class="mt-3 mb-3">Dstockgourmet - Mobile</h4>
            </div>
            
            <div class="card col-md-3 col-sm-3 col-6 mb-5 mx-auto"><a href="https://www.figma.com/file/EmjHCpQJ8uF5sueSgu1yyt/Parrot-Fish-Design-(Mobile)?type=design&node-id=401%3A2&mode=design&t=jGyyI8uR9LXpKFy7-1" target="_blank"><img class="w-100" src="./img/figma-parrotfish-img.jpg" alt="parrotfish"></a>
              <h4 class="mt-3 mb-3">Parrotfish - Mobile</h4>
            </div>
          </div>

          <div class="d-lg-flex d-md-flex d-sm-flex justify-content-around mt-5">
            
            <div class="card col-md-3 col-sm-3 col-6 mb-5 mx-auto"><a href="https://www.figma.com/file/YY8iWygT73c1f8VCRO7N1k/Dise%C3%B1o-Avanzado-para-Nicksan-(Desktop)?type=design&mode=design&t=pkyHKoggqa48hGtU-1" target="_blank"><img class="w-100" src="./img/nicksan-desktop-img.jpg" alt="nicksan"></a>
              <h4 class="mt-3 mb-3">Nicksan - Desktop</h4>
            </div>
            
            <div class="card col-md-3 col-sm-3 col-6 mb-5 mx-auto"><a href="https://www.figma.com/file/9h2H3soIVROPT0QSTzkri5/Dstock--wireframe-(Desktop)?type=design&mode=design&t=pkyHKoggqa48hGtU-1" target="_blank"><img class="w-100" src="./img/dstock-desktop-img.jpg" alt="dstock"></a>
              <h4 class="mt-3 mb-3">Dstockgourmet - Desktop</h4>
            </div>
            
            <div class="card col-md-3 col-sm-3 col-6 mb-5 mx-auto"><a href="https://www.figma.com/file/2oYrEsqcp8iHOcSKnMPxan/Parrot-Fish-Design-(Desktop)?type=design&mode=design&t=pkyHKoggqa48hGtU-1" target="_blank"><img class="w-100" src="./img/parrotfish-desktop-img.jpg" alt="parrotfish"></a>
              <h4 class="mt-3 mb-3">Parrotfish - Desktop</h4>
            </div>
          </div>

        </div>


          

      </div>
   
  </div>

  <div class="row gx-0">
            <h3 class="lineUp mb-5">Mi Curriculum</h3>

            <div class="col-lg-6 col-md-12 d-lg-flex justify-content-lg-end d-md-flex justify-content-md-center d-flex justify-content-center"><img class="cv-style" src="../src/img/cv-img.png" alt=""></div>
            <div class="col-lg-6 col-md-12 d-lg-flex justify-content-lg-start  d-flex justify-content-center align-items-center"><a href="josueroloncv.pdf"><button class="btn float-start ml-10 px-5 btn-download mx-5">Descargar curriculum</button></a></div>
          </div>


  <div class="row mt-5 mt-10 gx-0">
            <h3 class="lineUp">Contacto</h3>
  </div>

  <footer class="footer mt-10 footer-st" >
    
    <div class="waves">
      <div class="wave" id="wave1"></div>
      <div class="wave" id="wave2"></div>
      <div class="wave" id="wave3"></div>
      <div class="wave" id="wave4"></div>
    </div>
    
    
    <ul class="social-icon">
      <li class="social-icon__item"><a class="social-icon__link" href="tel:+523221344263" target="_blank">
          <i class="fa fa-whatsapp d-inline-flex align-items-center"><p class="mx-4 icon-text">3221344263</p></i> 
        </a></li>
        <li class="social-icon__item"><a class="social-icon__link" href="https://github.com/josue-rolon-ramirez" target="_blank">
        <i class="fa fa-github d-inline-flex align-items-center"><p class="mx-4 icon-text">github.com/josue-rolon-ramirez</p></i> 
        </a></li>
      <li class="social-icon__item"><a class="social-icon__link" href="https://gitlab.com/XNAMELESSY" target="_blank">
        <i class="fa fa-gitlab d-inline-flex align-items-center"><p class="mx-4 icon-text">gitlab.com/XNAMELESSY</p></i> 
        </a></li>
      <li class="social-icon__item"><a class="social-icon__link" href="https://www.linkedin.com/in/josue-rolon-ramirez-2545a0217/" target="_blank">
        <i class="fa fa-linkedin d-inline-flex align-items-center"><p class="mx-4 icon-text">Linkedin - Josué Rolón Ramírez</p></i>
        </a></li>
    </ul>
  
   
  </footer>

</template>


<script>

  
 
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';

  import 'swiper/css/pagination';

  import './assets/bootstrap/swiper-styles.css';

  // import required modules
  import { Pagination } from 'swiper/modules';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Pagination],
      };
    },
  };



</script>
