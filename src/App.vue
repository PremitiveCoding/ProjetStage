<template>
  <NavBar />
  <HeaderSection />
  <AboutSection />
  <ServiceSection />
  <ProcessSection />
  <RealisationsSection />
  <TestimonialsSection />
  <ClientsSection />
  <ContactSection />
  
  <!-- End Clients Section -->
</template>

<script>
import NavBar from "./components/NavBar.vue";
import HeaderSection from "./components/HeaderSection.vue";
import AboutSection from "./components/AboutSection.vue";
import ServiceSection from "./components/ServiceSection.vue";
import ProcessSection from "./components/ProcessSection.vue";
import RealisationsSection from "./components/RealisationsSection.vue";
import TestimonialsSection from "./components/TestimonialsSection.vue";
import ClientsSection from "./components/ClientsSection.vue";
import ContactSection from "./components/ContactSection.vue";
export default {
  name: "App",
  components: {
    NavBar,
    HeaderSection,
    AboutSection,
    ServiceSection,
    ProcessSection,
    RealisationsSection,
    TestimonialsSection,
    ClientsSection,
    ContactSection
},
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
.test{
  width : 100%;
  height : 300px;
  background-color: #012970;
}
.carousel {
  background-image: linear-gradient(rgba(18,151,245,0.94), rgba(11,148,246,0.92)),
    url("https://www.realease-capital.fr/wp-content/uploads/2017/03/visuel-erreur-pas-commetre-062020.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: left top;
  height : 400px;
}
/* Since positioning the image, we need to help out the caption */
.carousel-caption {
  bottom: 3rem;
  z-index: 10;
}

.carousel-item {
  height: 200px;
}


.carousel-item > img {
  position: absolute;
  top: 0;
  left: 0;
  min-width: 100%;
  height: 32rem;
}
nav {
  position: inherit;
  top: 0%;
}

.scrolled {
  background-color: #012970;
}

.navbar-light {
  background-color: rgba(0, 0, 0, 0);
}
.bg-navbar{
  background : #0a9aff;
}
.navbar-nav {
  margin-right: 60px;
  height: 33px;
}
.nav-item{
  margin-top: -6px;
}
.nav-item a p {
  color: white;
  font-size: 14px;
  text-transform: uppercase;
}
.colorgray{
  color : gray;
}

.nav-item a p:hover {
  color: #f3ba44;
}

.devis {
  text-transform: uppercase;
  font-weight: bold;
  margin-top: 10px;
}
.btn-navbar {
  border: 2px solid #f3ba44;
  border-radius: 0%;
}
.devisnewclass {
  border: 2px solid black;
  border-radius: 0%;
  color: white;
}
.logoimg {
  width: 130px;
}

header {
  position: relative;
  background-color: black;
  height: 100vh;
  width: 100%;
  overflow: hidden;
}

header video {
  position: absolute;
  top: 50%;
  left: 50%;
  min-width: 100%;
  min-height: 100%;
  width: auto;
  height: auto;
  z-index: 0;
  -ms-transform: translateX(-50%) translateY(-50%);
  -moz-transform: translateX(-50%) translateY(-50%);
  -webkit-transform: translateX(-50%) translateY(-50%);
  transform: translateX(-50%) translateY(-50%);
}

header .container {
  position: relative;
  z-index: 2;
}

header .overlay {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background-color: #0f3d80;
  opacity: 0.8;
  z-index: 1;
}

.herosection {
  opacity: 1;
}

.herotitle {
  text-transform: uppercase;
}

.herop {
  width: 50%;
  margin: 0 auto;
  font-size: 13px;
  font-weight: 500;
}

.herobtn {
  text-transform: uppercase;
  margin-top: 18px;
  border: 3px solid #f3ba44;
  border-radius: 0%;
  color: white;
  font-weight: bolder;
  font-size: 13px;
  padding: 12px;
}

.about {
  background-image: url("header-background.jpg");
  background-size: cover;
  background-position: center right;
}

.about .content {
  background-color: #f6f9ff;
  padding: 40px;
}

.about h3 {
  font-size: 14px;
  font-weight: 700;
  color: #4154f1;
  text-transform: uppercase;
}

.about h2 {
  font-size: 24px;
  font-weight: 700;
  color: #012970;
}

.about p {
  margin: 15px 0 30px 0;
  line-height: 24px;
}

.about .btn-read-more {
  line-height: 0;
  padding: 15px 40px;
  border-radius: 4px;
  transition: 0.5s;
  color: #fff;
  background: #4154f1;
  box-shadow: 0px 5px 25px rgba(65, 84, 241, 0.3);
}

.about .btn-read-more span {
  font-family: "Nunito", sans-serif;
  font-weight: 600;
  font-size: 16px;
  letter-spacing: 1px;
}

.about .btn-read-more i {
  margin-left: 5px;
  font-size: 18px;
  transition: 0.3s;
}

.about .btn-read-more:hover i {
  transform: translateX(5px);
}

.trait {
  width: 80px;
  height: 4.5px;
  background-color: #0a9aff;
  margin-top: 6.6px;
  margin-left: -83px;
}

.abouttitle {
  display: flex;
}

.texttitleabout {
  margin-left: 6px;
  text-transform: uppercase;
  font-weight: lighter;
  color: black;
}

.about-video iframe {
  width: 80%;
  height: 50vh;
  text-align: center;
  margin: 0 auto;
  display: flex;
  justify-content: center;
}

.aboutbtn {
  border: 3.5px solid #f3ba44;
  border-radius: 0%;
  padding: 9px;
  font-weight: 900;
  text-transform: uppercase;
  font-size: 14px;
  color: #f3ba44;
  text-align: left;
}

section {
  padding: 60px 0;
  overflow: hidden;
}

.section-bg {
  background-color: #f4f9fc;
}
.about .traitvertical {
  width: 3px;
  height: 44px;
  background-color: #0a9aff;
  margin: 0 auto;
  top: 66px;
  position: relative;
  margin-top: -66px;
}
.section-title .traitvertical {
  text-align: center;
  width: 3px;
  height: 44px;
  background-color: #0a9aff;
  margin: 0 auto;
  margin-top: -60px;
}
.section-title2 .traitvertical {
  text-align: center;
  width: 3px;
  height: 44px;
  background-color: #0a9aff;
  margin: 0 auto;
  margin-top: -60px;
}
.services .traitvertical2 {
  width: 3px;
  height: 44px;
  background-color: #0a9aff;
  margin: 0 auto;
  top: 66px;
  position: relative;
  margin-top: -50px;
}

.process .traitvertical2 {
  width: 3px;
  height: 44px;
  background-color: #0a9aff;
  margin: 0 auto;
  position: relative;
  margin-top: -66px;
}
.process .traitvertical3 {
  width: 3px;
  height: 44px;
  background-color: #0a9aff;
  margin: 0 auto;
  position: relative;
  top: 60px;
}
.clients .traitvertical3{
  width: 3px;
  height: 44px;
  background-color: #0a9aff;
  margin: 0 auto;
  position: relative;
  top: 35px;
}
.section-title p {
  text-transform: uppercase;
  font-size: 15px;
  text-align: center;
  margin-top: 20px;
  color: black;
  opacity: 68%;
  
}
.section-title2 p{
  text-transform: uppercase;
  font-size: 15px;
  text-align: center;
  margin-top: 20px;
  opacity: 100%;
  font-weight: light;
  font-family: open Sans;
  opacity: 88%;
}
.feature-1 .wrap-icon {
  margin: 0 auto;
  height: 100px;
  width: 100px;
  border-radius: 50%;
  position: relative;
  margin-bottom: 30px;
  box-shadow: 0 15px 22px 0 rgba(0, 0, 0, 0.24);
  display: inline-flex;
  align-items: center;
  justify-content: center;
}

.feature-1 .wrap-icon.icon-1 {
  background: #e9e9e9;
}

.feature-1 .wrap-icon i {
  font-size: 38px;
  line-height: 0;
  color: #19a5fe;
}

.feature-1 h3 {
  font-size: 18px;
}

.feature-1 p {
  color: black;
  font-weight: light;
  font-size: 12px;
}

.section-heading {
  width: 100%;
  font-weight: 700;
  color: black;
  font-family: 'Roboto';
  text-transform: uppercase;
}

.section-p {
  font-size: 13px;
}

.services {
  background-color: #f5f5f5;
}

.clients {
  padding: 33px 100px;
  text-align: center;
}
@media (max-width: 768px) {
  .clients {
  padding: 33px 0px;
}
}
.clients img {
  max-width: 75%;
  transition: all 0.4s ease-in-out;
  display: inline-block;
  padding: 15px 0;
}
.carousel-caption {
  color: white;
}
.clients img:hover {
  filter: none;
  transform: scale(1.15);
}
.contact{
    width : 75%;
    margin : 0 auto;
    margin-top: -42px;
}
.contactsection{
  background-image: linear-gradient(rgba(6,44,112,0.93), rgba(22,54,112,0.88)),url('https://www.itespresso.fr/wp-content/uploads/2019/12/img-itespresso-684x513.jpg') ;
  background-repeat: no-repeat;
  background-size: cover;
  backdrop-filter: center left;
}
.submitbtn{
    font-weight: bolder;
    padding: 8px 28px;
    text-transform: uppercase;
    font-size: 14px;
    border: 2.8px solid #f3ba44;   
    background : rgba(0, 0, 0,0) ;
}
.form-control{
    background : rgba(0, 0, 0,0);
    border-bottom: 1.5px solid gray; 
    border-top: 0;
    border-left: 0;
    border-right: 0;
}
.submitbtn:hover{
    background-color: #f3ba44;    
    color:white;
}
.coordonnees{
  margin-top: 16px;
  margin-bottom: -14px;
}
.contactemail{
  font-weight: bolder;
  font-size: 16px;
  font-family: 'Poppins', open Sans;
}
.contactnumber{
  font-size: 20px;
  font-weight: bolder;
  margin-top: -5px;
  font-family: 'Poppins', open Sans;
}
.realisations{
  background-color: #f5f5f5;
}
.realisationscontainer{
  width : 88%;
  margin: 0 auto;
  margin-top: -15px;
}

.realisationtitle{
  font-family: 'Poppins', sans-serif;
  font-weight: light;
  font-size: 18px;
  margin-top: 8px;
}
.realisationtitle a{
  text-decoration: none;
  color : #243952;
}
.realisationp{
  font-family: 'Open Sans', sans-serif;
  margin-top: -15px;
}
.gaptitletestimonial{
  height: 20px;
}
.containercarousel{
  margin-top: 30px;
  height : 200px;
}
.titlecarousel{
  margin : 0 auto;
  display: flex;

}
.quote{
  display: flex;
  margin : 0 auto;
  justify-content: center;
}
.quoteimg{
  width: 40px;
  height: 40px;
  margin: 0 40px;
}
.textquote{
  font-family: open Sans;
    font-weight: normal;
    font-size: 15px;
    color: #fff;
    text-align: center;
    float: left;
    line-height: 19px;
}

@media (max-width: 900px) {
  .containercarousel{
  margin-top: -100px;
}
.quoteimg{
  margin: 0 10px;
}
.carousel-item {
  height: 300px;
}
.carousel-caption{
  height: 300px;
  margin-top: 30px;
}
.carousel{
  width: 500px;
}
}
@media (max-width: 500px) {
  .containercarousel{
  margin-top: 0px;
}
.realisationscontainer{
  width : 100%;
}


}

.personne{
   font-family: 'Poppins', open Sans;
    font-size: 14px;
    color: #fff;
    text-align: center;
    text-transform: uppercase;
    display: inherit;
    margin-bottom: 0px !important;
}
.societe{
  font-family: 'Open Sans', sans-serif;
}
.footer{
  margin-top: -30px;
  padding: 0;
  width :70%;
  text-align: center;
  margin: 0 auto;
}
.bi-suit-heart-fill{
  color : red;
}
.realiseavec{
  text-align: left;
  font-family: 'Poppins', open Sans;
  font-size: 12px;
  font-weight: light;
}
hr{
  color : white;
  border: 0.6px solid white;
}
.socialmedia{
  text-align: right;
  margin-top: -41px;
}
.socialmedia i {
  margin : 0 9px;
  color: white;
}
@media (max-width: 768px) {
  .clients img {
    max-width: 40%;
  }
}
@media (max-width: 768px) {
  .nav-item a p{
    color : gray;
  }
  .navbar-nav{
    height: 90vh;
  }
  .devis{
    text-align: center;
  }
  .navbar-collapse ul{
    margin-top: 22px;
  }
 
}

/*--------------------------------------------------------------
@media (min-width: 768px) {
  .col-sm-4 {
    width: 33.33333333%;
  }
}
/* Media Query for devices withi coarse pointers and no hover functionality */

/* This will use a fallback image instead of a video for devices that commonly do not support the HTML5 video element */

@media (pointer: coarse) and (hover: none) {
  header {
    background: url("https://source.unsplash.com/XT5OInaElMw/1600x900") black no-repeat
      center center scroll;
  }
  header video {
    display: none;
  }
}
</style>
