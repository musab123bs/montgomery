<template>
    <div>
        <section class="footer">
            <div class="container">
                <div class="row main-footer">
                    <div class="col-md-4 col-sm-6 footer-cont">
                            <div class="inner-footer-content">
                                <div class="footer-logo contentVisible">
                                    <img src="../assets/img/logo.png" alt="footer-logo">
                                </div>
                                <div class="footer-heading">
                                    <h2>Montgomery <br>Fire Department</h2>
                                    <p>136 Ward Street</p>
                                    <p>Montgomery, NY 12549</p>
                                    <p class="call-link"><a href="#">Non-Emergency (845) 457-3205</a></p>
                                </div>
                            </div>
                    </div>
                    <div class="col-md-4 col-sm-6 footer-cont">
                        <div class="inner-footer-content">
                            <div class="footer-subheading">
                                <h3>Quick Links</h3>
                            </div>
                            <div class="footer-items">
                                <ul>
                                    <li><a class="active" href="#">News & Events </a></li>
                                    <li><a href="#">Media Gallery</a></li>
                                    <li><a href="#">Fire Safety</a></li>
                                    <li><a href="#">Apparatus</a></li>
                                    <li><a href="#">Meetings</a></li>
                                    <li><a href="#">Fire District</a></li>
                                </ul>
                            </div>
                        </div>
                </div>
                <div class="col-md-4 footer-cont">
                    <div class="inner-footer-content">
                        <div class="footer-subheading">
                            <h3>Contact</h3>
                        </div>
                        <div class="footer-form">
                            <form name="myForm" action="action_page.html" method="post">
                                <input type="text" name="fname" placeholder="Name" class="form-control" required>
                                <input type="email" name="email" placeholder="Email" class="form-control" required>
                                <input type="text" name="phnNo" placeholder="Phone Number" class="form-control" required>
                                <textarea name="message" id="message" class="form-control" placeholder="Message" rows="10"></textarea>
                                <input type="submit" value="Submit">
                              </form>
                        </div>
                    </div>
            </div>
                </div>
            </div>
            <div class="uparrow" >
                <a href="#banner"><i class="fa-solid fa-angle-up"></i></a>
            </div>
        </section>
        <div class="copyright text-center">
            <p>© 2022 Montgomery Fire Rescue. All Rights Reserved.<br class="break">
                Website by <a href="https://www.belsito.com/" >Belsito Communications Inc.</a></p>
        </div>
    </div>
</template>


<script>
export default {
    name : 'OurFooter'
}
</script>

<style>

.footer {
    background-position: center;
    background-size: cover;
    height: 100%;
    position: relative;
}
.footer:before {
    position: absolute;
    content: '';
    background-color: #000000;
    height: 100%;
    width: 100%;
    top: 0;
    left: 0;
}
.footer .main-footer .footer-cont:nth-child(2) {
    display: flex;
    align-items: flex-end;
}
.footer .main-footer .footer-cont:nth-child(2) .inner-footer-content {
    display: flex;
    align-items: center;
    height: 333px;
    line-height: 4;
    align-items: flex-end;
}

.footer .main-footer .footer-cont .inner-footer-content .footer-heading .call-link a {
    color: #baaaa6;
}
.footer .main-footer {
    position: relative;
    color: #fff;
    display: flex;
    align-items: flex-start;
}
.footer .main-footer .footer-cont {
}
.footer .main-footer .footer-cont .inner-footer-content {}
.footer .main-footer .footer-cont .inner-footer-content .footer-logo {
    width: 12rem;
    margin-bottom: 2rem;
}
.footer .main-footer .footer-cont .inner-footer-content .footer-logo img {}
.footer .main-footer .footer-cont .inner-footer-content .footer-heading {
    font-family: 'Roboto';
    text-align: left;
}
.footer .main-footer .footer-cont .inner-footer-content .footer-heading h2 {}
.footer .main-footer .footer-cont .inner-footer-content .footer-heading p {
    color: #baaaa6;
}
.footer .main-footer .footer-cont .inner-footer-content .footer-heading .call-link {}
.footer .main-footer .footer-cont .inner-footer-content .footer-subheading {}
.footer .main-footer .footer-cont .inner-footer-content .footer-subheading h3 {
    padding-bottom: 1.2rem;
    color: #e78600;
    display: none;
}
.footer .main-footer .footer-cont .inner-footer-content .footer-items {height: fit-content;}
.footer .main-footer .footer-cont .inner-footer-content .footer-items ul {
    padding: 0;
    text-align: left;
}
.footer .main-footer .footer-cont .inner-footer-content .footer-items ul li {}
.footer .main-footer .footer-cont .inner-footer-content .footer-items ul li a {
    color: #ffffff;
    font-family: 'Poppins', sans-serif;
}
.footer .main-footer .footer-cont .inner-footer-content .footer-form {}
.footer .main-footer .footer-cont .inner-footer-content .footer-form form {}
.footer .main-footer .footer-cont .inner-footer-content .footer-form form input,
.footer .main-footer .footer-cont .inner-footer-content .footer-form form textarea {
    margin-bottom: 1.2rem;
    padding: 0.5rem;
    font-size: 1.4rem;
    border-radius: 0;
}
.footer .main-footer .footer-cont .inner-footer-content .footer-form form input::placeholder,
.footer .main-footer .footer-cont .inner-footer-content .footer-form form textarea::placeholder {
    color: #bdbdbd;
}
.footer .main-footer .footer-cont .inner-footer-content .footer-form form input:last-child {
    margin-top: 1rem;
    outline: none;
    border: 0.1rem solid #fff;
    padding: 1rem 4rem;
    font-size: 1.7rem;
    font-weight: 800;
    color: #fff;
    background-color: #2d2d2d;
}
.footer .main-footer .footer-cont .inner-footer-content .footer-form form textarea {
    border-radius: 0;
    outline: 0;
    border: 0;
}
.copyright {
    background-color: #df0114;
    color: #fff;
}
.copyright p {
    padding: 2.3rem 1.5rem;
}
.copyright p a {
    color: #fff;
    text-decoration: none;
}
.uparrow {
    width: 5rem;
    height: 5rem;
    background-color: #e78600;
    position: fixed;
    bottom: 6%;
    right: 3%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    display: none;
    z-index: 9999999;
}
.uparrow i {
    font-size: 3rem;
}
.uparrow a  {
    color: #fff;
}
.uparrow.fixed-arrw {
    display: flex;
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