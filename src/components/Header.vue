<template>
  <div>
    <div class="header">
      <div class="container-fluid">
        <div class="header-content">
          <div class="logo-holder">
            <img src="../assets/img/logo.png" alt="logo" />
            <p class="logo-tag">
              Montgomery<span><br />Fire Department</span>
            </p>
          </div>
          <div class="nav-menu">
            <ul class="dest-menu-list">
              <li><a class="active" href="#">News & Events </a></li>
              <li><a href="#">Media Gallery</a></li>
              <li><a href="#">Fire Safety</a></li>
              <li><a href="#">Apparatus</a></li>
              <li><a href="#">Meetings</a></li>
              <li><a href="#">Fire District</a></li>
            </ul>
          </div>
          <div class="mob-menu">
            <ul>
              <li><a class="active" href="#">News & Events </a></li>
              <li><a href="#">Media Gallery</a></li>
              <li><a href="#">Fire Safety</a></li>
              <li><a href="#">Apparatus</a></li>
              <li><a href="#">Meetings</a></li>
              <li><a href="#">Fire District</a></li>
            </ul>
          </div>
          <div class="mob-toggle">
            <span class="line line-1"></span>
            <span class="line line-2"></span>
            <span class="line line-3"></span>
          </div>
        </div>
      </div>
    </div>
    <section class="home-banner" id="banner" >
            <div class="slider">
               <div class="container">
                <div class="banner-content">
                    <div class="row main-banner-content">
                        <div class="col-md-6 banner-col banner-left">
                         <p><span class="color-red fadeEffect">To Preserve Life</span> & property, promote <span class="color-orange">public safety</span> & fire prevention through leadership, 
                         management & actions.</p>
                        </div>
                        <div class="col-md-6 banner-col banner-right">
                            <div class="banner-right-img-holder">
                                <img src="../assets/img/banner-right.jpg" alt="banner-right" class="beats">
                            </div>
                        </div>
                    </div>
                </div>
               </div>
            </div>
        </section>
  </div>
</template>

    <script>
export default {
  name: "TopHeader",
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,500;1,700;1,900&family=Signika:wght@300;400;500;600;700&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  clear: both;
  transition: 0.3s;
}
body#bodyLoad {
  opacity: 0;
  transition: 0.8s;
}
html {
  font-size: 62.5%;
}
html body {
  font-family: "Roboto", sans-serif;
  background-color: #ff8401;
  overflow-x: hidden;
}

/* scroll sidebar */

::-webkit-scrollbar {
  width: 0.5rem;
}

::-webkit-scrollbar-track {
  background: #000;
}

::-webkit-scrollbar-thumb {
  background: #f01313;
  border-radius: 0rem;
}

::-webkit-scrollbar-thumb:hover {
  background-image: linear-gradient(#ff8400, #fcc245);
}

.contentLoad {
  content-visibility: auto !important;
  contain-intrinsic-size: 0 100vh !important;
}
.color-orange {
  color: #ff8400;
}

.color-red {
  color: #f01313;
}
.fixed {
  position: fixed !important;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 999999;
  background-color: #ffffff;
}

section {
  padding: 7rem 0.7rem;
}
.full-column-wdth {
  padding: 4rem 0;
  text-align: center;
  margin-top: 1rem;
  color: #fff;
}
.theme-yellow {
  background-color: #fcc245;
}
.theme-pink {
  background-color: #e9292a;
}
.color-wht {
  color: #fff;
}
.color-blk {
  color: #000;
}
.theme-orange {
  background-color: #ff7e00;
}
section.company-status {
  background: linear-gradient(90deg, rgb(107 107 107 / 0%) 0%, rgb(0 0 0) 80%),
    url(../assets/img/wanted-heros.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: right 50% top 5%;
  height: 65.7rem;
  display: grid;
  place-items: center;
}
img {
  width: 100%;
}
a,
p {
  font-size: 2rem;
  line-height: 1.5;
  margin: 0 !important;
}
a {
  text-decoration: none !important;
}
a:hover {
  color: #ffffff !important;
}
ul {
  list-style: none;
  padding: 0;
}
h1 {
  font-size: 3.2rem;
}
h2 {
  font-size: 2.4rem;
}
h3 {
  font-size: 1.872rem;
}
h4 {
  font-size: 1.6rem;
}
h5 {
  font-size: 1.328rem;
}
h6 {
  font-size: 1.072rem;
}
.theme-main-heading {
  font-family: "Roboto", sans-serif;
}
 {
}
.header {
  background-color: #ffffff;
  box-shadow: 1px 2px 5px #000;
}
.header .header-content {
  display: flex;
  justify-content: space-between;
  padding: 0 8rem;
  height: 8rem;
  position: relative;
  align-items: center;
}
.header-content.fixed {
  box-shadow: 1px 2px 5px #ddd;
}
.header-content.fixed ul {
}
.header-content.fixed .mob-menu.active {
  left: 23%;
}
.header .header-content .logo-holder {
  display: flex;
  position: relative;
  z-index: 2;
  align-items: center;
  width: 200px;
}
.header .header-content .nav-menu .dest-menu-list li .active {
  /* color: #fff; */
}
.header .header-content .logo-holder img {
  width: 31%;
  position: relative;
  filter: drop-shadow(3px 3px 2px #0006);
}
.header .header-content .logo-holder .logo-tag {
  padding-left: 1rem;
  color: #000000;
  font-size: 2.4rem;
  gap: 3px;
  font-family: "Poppins";
  line-height: 1;
  text-align: center;
  font-weight: 600;
}
.header .header-content .nav-menu {
}
.header .header-content .nav-menu .dest-menu-list {
  padding: 0;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  height: 8rem;
  list-style: none;
  gap: clamp(1rem, 1.2vw, 3rem);
}
.header .header-content .nav-menu .dest-menu-list li a {
  text-decoration: none;
  color: #000000;
  font-family: "Signika", sans-serif;
  transition: 0.5s;
}
.header .header-content .nav-menu .dest-menu-list li a:hover {
  color: #e10004 !important;
}
.header .header-content .nav-menu {
}

.header .header-content .logo-holder .logo-tag span {
  color: #534a4a;
  font-size: 1.8rem;
  font-weight: 600;
}

/* mob menu */

.header .mob-menu {
  background-color: #303030c7;
  position: fixed;
  height: 100vh;
  top: 50%;
  left: -80%;
  transform: translate(-50%, -50%);
  z-index: 55;
  width: 48vw;
  transition: 1s;
}

.header .mob-menu.active {
  left: 23%;
}
.header .mob-menu {
  background-color: #303030c7;
  position: fixed;
  height: 100vh;
  top: 50%;
  left: -80%;
  transform: translate(-50%, -50%);
  z-index: 55;
  width: 48vw;
  transition: 1s;
}

.header .mob-menu.active {
  left: 23%;
}
.header .mob-menu ul {
  display: flex;
  flex-direction: column;
  z-index: 666;
  list-style: none;
  padding: 0;
  text-align: center;
  justify-content: center;
  gap: 13px;
  height: 100%;
}
.header .mob-menu ul li {
  filter: drop-shadow(2px 2px 1px #000);
}
.header .mob-menu ul li a {
  color: #fff;
  font-weight: 900;
}
.header .mob-toggle {
  flex-direction: column;
  justify-content: center;
  display: none;
  padding: 2.4rem;
  background-color: rgb(204 0 4);
  height: 100%;
  overflow: hidden;
  position: relative;
  transition: 0.5s;
}
.header .mob-toggle.active {
  background-color: #e78600;
}
.header .mob-toggle .line {
  color: #fff;
  height: 0.3rem;
  width: 3rem;
  display: flex;
  background-color: #fff;
  flex-direction: column;
  position: absolute;
  transition: 0.4s;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
span.line.line-3 {
}
.header .mob-toggle .line:last-child {
}
.header .mob-toggle.active .line-1 {
  top: 50%;
  transform: translateX(-50%) rotate(-45deg);
}
.header .mob-toggle.active .line-2 {
  top: 50%;
  transform: translateX(-50%) rotate(-45deg);
}
.header .mob-toggle.active .line-3 {
  top: 50%;
  transform: translateX(-50%) rotate(45deg);
}
.header .mob-toggle .line-1 {
  top: 30%;
}
.header .mob-toggle .line-3 {
  top: 73%;
}

/* banner  */

.main-banner-content {
    display: flex;
    align-items: center;
}
.banner-right-img-holder {
    overflow: hidden;
}
.main-banner-content .banner-col {
    margin: 4rem 0;
}
.main-banner-content .banner-left {
}
.main-banner-content .banner-left p {
    font-size: 3.5rem;
    font-family: 'Signika';
    color: #fff;
    line-height: 1.2;
    padding: 0 1rem;
}
.main-banner-content .banner-left p > span {
    font-size: 4.2rem;
}
.main-banner-content .banner-left p > span + span {
    font-size: 3.5rem;
}
.main-banner-content .banner-right {
    position: relative;
    z-index: 1;
    padding: 0;
}

.main-banner-content .banner-right:before {
    position: absolute;
    top: -1.5rem;
    left: 1.5rem;
    height: 100%;
    width: 100%;
    background-color: #ff8401;
    content: '';
    z-index: -1;
}
  .home-banner {
    background-image: url(../assets/img/overlaybanner.jpg);
    height: 53.7rem;
    position: relative;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 100% 10%;
    width: 100%;
    padding: 0;
    display: grid;
    clip-path: polygon(50% 3%, 100% 0, 100% 93%, 50% 98%, 0 93%, 0 0);
}
  .home-banner .slider {
    display: grid;
    place-items: center;
}
  .home-banner .slider .slider-items {}
  .home-banner .slider .slider-items img {
    width: 100%;
}
  .home-banner .slider .slider-content {
    position: absolute;
    top: 55%;
    left: 30%;
    transform: translate(-50%, -50%);
    color: #fff;
    width: 50%;
    transition: 0.5s;
}
  .home-banner .active .slider-content{
    opacity: 0.5;
}
  .home-banner .slider .slider-content h1 {
    font-size: clamp(2.2rem, 6.5vw, 7.2rem);
}
  .home-banner .slider .slider-content p {
    font-size: clamp(1.5rem, 3.5vw, 4rem);
    font-weight: 200;
    margin-bottom: 2rem;
}
  .home-banner .slider .slider-content a {
    text-decoration: none;
    color: #fff;
    text-transform: uppercase;
    padding: 1rem 2rem;
    background-color: #db391a;
    filter: drop-shadow(2px 2px 2px #000);
    transition: 0.5s;
}
  .home-banner .slider .slider-content a:hover {
    filter: drop-shadow(0px 0px 0px #000);
}


/* responive  */

@media only screen and (max-width: 1080px) {
  html {
    font-size: 50%;
  }
    .header .header-content,
    .header .header-content .nav-menu .dest-menu-list {
    height: 10rem;
  }
}

@media only screen and (min-width: 999px) {
  .mob-nav-menu {
    display: none;
  }
  .header .mob-menu {
    display: none;
  }
}

@media only screen and (max-width: 998px) {
  .header .header-content .nav-menu .dest-menu-list {
    display: none;
  }
  .header .header-content {
    padding: 0 4rem;
    display: flex;
    align-items: center;
    transition: 2s;
  }
  .header .mob-toggle {
    display: flex;
    align-content: center;
    height: 3.7rem;
  }
}

@media only screen and (max-width: 991px) {
  html {
    font-size: 45%;
  }
  .home-banner .slider .slider-content {
    top: 55%;
  }
  .header .header-content .logo-holder {
    margin-top: 0;
  }
  .header .header-content .logo-holder .logo-tag {
    padding-bottom: 0.5rem;
  }
  .comp-row .status-info p {
    line-height: 1;
  }
}
@media only screen and (min-width: 768px) {
  .news .inner-news-cont .news-headline p {
    font-size: 1.4rem;
  }
  .news .new-main-heading h1 {
    font-size: 3rem;
  }
}

@media only screen and (max-width: 767px) {
  .footer .main-footer {
    align-items: center;
  }
  .footer .main-footer .footer-cont:nth-child(2) {
    padding-top: 0rem;
  }
  .footer .main-footer .footer-cont:nth-child(1) {
    padding-bottom: 2rem;
  }
  .home-banner {
    height: auto;
  }
  .main-banner-content {
    padding: 10rem 4rem;
  }
  section.company-status {
    background-position: center;
  }
  .news .inner-news-cont {
    padding: 1rem;
  }
  .footer .main-footer .footer-cont:nth-child(2) .inner-footer-content {
    height: auto;
  }
}

@media only screen and (max-width: 380px) {
  .break {
    display: none;
  }
  .copyright p {
    padding: 2.3rem 1rem;
    line-height: 1;
    font-size: 1.8rem;
  }
  .copyright p a {
    font-size: 1.8rem;
  }
}
</style>