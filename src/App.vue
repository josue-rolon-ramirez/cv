<template>
  <div class="container mw-100">
    <div class="row">
      <div class="col-12 gx-0" id="bgfondo">

      </div>
    
        <div class="d-lg-flex profile-items">
      
        <div class="col-lg-5 col-md-12 col-sm-12 photo-profile-content  d-flex justify-content-lg-end justify-content-center align-items-center mt-5 mt-lg-0">
          <img src="../src/img/profile-photo.jpg" alt="photo-profile" class="photo-profile">
        </div>

        <div class="col-lg-6 col-md-12 col-sm-12 text-center d-flex justify-content-lg-start justify-content-center align-items-center mt-5 mt-lg-0" >
          <div>
          <h2 class="illuminated-text mx-lg-5">Josué Rolón Ramírez</h2>  
          <h3 class="illuminated-text mx-lg-5">Desarrollador web &<br> Product Manager</h3>
          </div>
        </div> 

      </div>
      
      </div>

      <div class="row">
        <h3 class="lineUp">Conocimientos</h3>
        </div>
        

      <div class="row swiper-content d-flex justify-content-center">
        <div class="col-lg-12 col-11">
        <swiper 
    :slidesPerView="3"
    :spaceBetween="70"
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
    <swiper-slide><img src="./img/vue-logo.png" alt="vue-image"></swiper-slide>
    <swiper-slide><img src="./img/wordpress-logo.png" alt="wordpress-image"></swiper-slide>
    <swiper-slide><img src="./img/figma-logo.png" alt="figma-image"></swiper-slide>
    <swiper-slide><img src="./img/git.png" alt="git-image"></swiper-slide>
    <swiper-slide><img src="./img/scrum-icon.png" alt="scrum-image"></swiper-slide>
   
  </swiper>

        </div>
     </div>

     <div class="row mb-5 mx-5">
        <h3 class="lineUp">Acerca de mi</h3>
        <div class="d-block justify-content-center text-content">
          
          <p class="col-12 mt-5">Soy Josué Rolón Ramírez soy <b>Desarrollador Web</b> y <b>Product Manager</b> de Puerto Vallarta. Soy ingeniero en computación
            y me apasiona no solo escribir código, sino también entender el panorama completo de un producto tecnológico para proponer
            soluciones ágiles, de alto impacto y eficientes. </p>
            
           <p class="col-12 mt-5"> En mi trayectoria, he tenido la oportunidad de desenvolverme en dos grandes áreas:</p>
              
            <ul>
              <li class="mt-5">Como <b>Desarrollador Web</b> en Marival Group durante un año y medio me enfoqué en el desarrollo frontend y backend,
                transformando prototipos de <b>Figma</b> en sitios web funcionales y optimizados con <b>Vue</b>, <b>Laravel</b> y <b>PHP</b>, además de gestionar servidores y rendimiento web.</li>
              <li class="mt-5">
                Como <b>Product Manager</b> en Villa Group durante más de un año y medio lideré la estrategia y coordinación de equipos (UX/UI, Desarrollo y QA)
                bajo la metodología <b>Scrum</b>, traduciendo necesidades de negocio en soluciones tecnológicas efectivas y entregadas a tiempo.
              </li>
            </ul>

            <p class="mt-5">
              Me fascina resolver problemas reales y colaborar de cerca con creativos y programadores para convertir ideas complejas en productos digitales excepcionales.
              Por eso, mantengo una mentalidad de crecimiento constante,buscando siempre dominar nuevas tecnologías y perfeccionar mis habilidades en todo lo que impulse
              el desarrollo de software.
            </p>
          
          </div>
        </div>


        <div class="row mb-5 mx-5">
        <h3 class="lineUp">Experiencia</h3>
        <div class="text-content">
          
            <h3>Product Manager - Villa Group & Spa</h3>
            <h4>Puerto Vallarta, Mex.</h4>
            <ul> 
              <li class="mt-3 bullet-points">Creación y documentación de Product Backlogs Items bajo metodologia de
                SCRUM asegurando correcto seguimiento en sitios web y sistema interno administrativo Eplat.</li>
              <li class="mt-3 bullet-points">Coordinación de prioridades de desarrollo en objetivos y necesidades criticas de los stakeholders</li>
              <li class="mt-3 bullet-points">Generar propuestas agiles para distintas areas de negocio (Pre-arrival, Marketing, Netcenter y Univarsidad Villagroup)
                  para entregas de soluciones tecnológicas de menor precio y mayor efectividad.</li>
              <li class="mt-3 bullet-points">Coordinacion activa con los equipos de UX/UI, Desarrollo y QA para asegurar el proceso de entrega de producto alineado
                  con las necesidades solicitadas por stakeholders.</li>
              <li class="mt-3 bullet-points">Programación de sesiones semanales sobre estatus con stakeholders para mantener transparencia en el progreso de los proyectos solicitados.</li>
              <li class="mt-3 bullet-points">Analisis preventivos y documentacion de bugs en modulos nuevos para prevencion de uso en operacion de cliente para asegurar el funcionamiento
                  correcto de producto en modulos de plataforma Eplat y sitios web</li>
              <li class="mt-3 bullet-points">Organizacion de historias de usuarios en Azure manteniendo logica de estructura para proyectos con multiples Features</li>
            </ul>
          
        
          <div class="mt-5"> 
            <h3>Desarrollador web - Marival Group</h3>
            <h4>Nuevo Nayarit, Mexico.</h4>
            <h4 class="mt-5">Desarrollo Frontend & Backend</h4>
            <ul> 
              <li class="mt-3 bullet-points">Optimización y desarrollo web de sitios web utilizando HTML,CSS, Javascript, PHP, haciendo integración y eliminación de contendidos
                 y componentes.</li>
              <li class="mt-3 bullet-points">Creación y personalización de sitios web basados en Wordpress</li>
              <li class="mt-3 bullet-points">Diseño y Desarrollo de mailings responsivos haciendo uso de framework MJML</li>
              <li class="mt-3 bullet-points">Edición de campos en base de datos sobre perfiles de usuarios para correcto funcionamiento de sistema utilizado Marival Access</li>
              <li class="mt-3 bullet-points">Manejo de versiones con Git & Github</li>
              
            </ul>

            <h4 class="mt-5">Diseño UX/UI</h4>
            <ul> 
              <li class="mt-3 bullet-points">Creación de prototipos y wireframes de media fidelidad en Figma para el planeamiento de interfaces web</li>
              <li class="mt-3 bullet-points">Edición de material gráfico en Photoshop para su correcta implementación y rendimiento en sitios web.</li>
            </ul>

            <h4 class="mt-5">Servidores</h4>
            <ul> 
              <li class="mt-3 bullet-points">Configuración, instalación y mantenimiento de servidores web a través de WHM y Webmin</li>
              <li class="mt-3 bullet-points">Gestión, configuraciones de DNS y rendimiento optimo de sitios web mediante Cloudflare</li>
            </ul>
          </div>
        

          </div>
        </div>
      
     <div class="row text-center mt-10">
        <div class="col-lg-6 col-md-12">
          <h3 class="lineUp">Proyectos Web</h3>
          <h4 class="st-h4">Diseño,desarrollo y estilos con:</h4>

          <div class="d-lg-flex justify-content-around mt-5">

            <div class="card col-lg-3 col-md-6  d-md-block col-sm-6 mb-md-5 mx-auto d-sm-block mb-sm-5 col-6 mb-5"><a href="https://nicksanmexico.com/" target="_blank"><img class="w-100" src="./img/nicksan-page-img.jpg" alt="nicksan"></a>
              <h4 class="mt-3 mb-4">Nicksan</h4>
            <div class="">
            <ul>
            <li>CMS Wordpress</li>
            <li>Html</li>
            <li>Css</li>
            <li>Figma</li>
            <p>(Proyecto actualizado por empresa)</p>
          </ul>
        </div> 
          </div>
          
          <div class="card col-lg-3 col-md-6 d-md-block col-sm-6 mb-md-5 mx-auto d-sm-block mb-sm-5 col-6 mb-5"><a href="https://dstockgourmet.com" target="_blank"><img class="w-100" src="./img/dstock-page-img.png" alt="dstock"></a>
            <h4 class="mt-3 mb-4">Dstockgourmet</h4>
            <ul>
            <li>CMS Wordpress</li>
            <li>Html</li>
            <li>Css</li>
            <li>Figma</li>
            <p>(Proyecto retirado por empresa)</p>
          </ul>
          </div>
          <!--
          <div class="card col-lg-3 col-md-6 d-md-block  col-sm-6 mb-md-5 mx-auto d-sm-block mb-sm-5 col-6 mb-5"><a href="https://nicksanmexico.com/" target="_blank"><img class="w-100" src="./img/crud-usuarios-img.jpg" alt="crud-usuarios"></a>
            <h4 class="mt-3 mb-4">Crud de usuarios</h4>
            <ul class="mx-auto">
            <li class="card-text">Html</li>
            <li class="card-text">Css</li>
            <li class="card-text">Php</li>
            <li class="card-text">Bootstrap</li>
          </ul>
          </div>
        -->
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

          <div class="mt-10">
            <h3 class="lineUp mb-5">Mi Curriculum</h3>
          </div>
          
          <div class="col-lg-6 col-md-12 d-flex d-lg-flex justify-content-lg-end d-md-flex justify-content-md-center justify-content-center"><img class="cv-style" src="../src/img/cv-img-2.png" alt=""></div>
          <div class="col-lg-6 col-md-12 d-flex d-lg-flex justify-content-lg-start d-md-flex justify-content-md-center justify-content-center align-items-center"><button class="btn ml-10 px-4 btn-download"><a href="../Josue_Rolon_Ramirez_CV.pdf" target="_blank" >Descargar curriculum</a></button></div>
          

      </div>
   
  </div>

  <div class="mt-10">
            <h3 class="lineUp mt-5">Contacto</h3>
  </div>
  <footer class="footer footer-st d-flex">
    <!--
    <div class="waves">
      <div class="wave" id="wave1"></div>
      <div class="wave" id="wave2"></div>
      <div class="wave" id="wave3"></div>
      <div class="wave" id="wave4"></div>
    </div>
  -->
    
    <ul class="social-icon">
      <li class="social-icon__item mb-sm-5 mb-xs-5 col-md-6 d-flex justify-content-center"><a class="social-icon__link" href="tel:+523221344263" target="_blank">
          <i class="fa fa-whatsapp d-flex align-items-center"><p class="mx-4 icon-text">3221344263</p></i> 
        </a></li>
        <li class="social-icon__item mb-sm-5 mb-xs-5 col-md-6 d-flex justify-content-center"><a class="social-icon__link" href="https://github.com/josue-rolon-ramirez" target="_blank">
        <i class="fa fa-github d-flex align-items-center"><p class="mx-4 icon-text">github.com/josue-rolon-ramirez</p></i> 
        </a></li>
      <li class="social-icon__item mb-sm-5 mb-xs-5 col-md-6 d-flex justify-content-center"><a class="social-icon__link" href="https://gitlab.com/XNAMELESSY" target="_blank">
        <i class="fa fa-gitlab d-flex align-items-center"><p class="mx-4 icon-text">gitlab.com/XNAMELESSY</p></i> 
        </a></li>
      <li class="social-icon__item mb-sm-5 mb-xs-5 col-md-6 d-flex justify-content-center"><a class="social-icon__link" href="https://www.linkedin.com/in/josue-rolon-ramirez-2545a0217/" target="_blank">
        <i class="fa fa-linkedin d-flex align-items-center"><p class="mx-4 icon-text">Linkedin - Josué Rolón Ramírez</p></i>
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
