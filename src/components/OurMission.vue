<template>
    <section class="main-about">
            <div class="container">
                <div class="row inner-about">
                    <div class="col-md-6 col-lg-7 col-sm-7 col-xs-12 col-12 about-content abt-left">
                        <div class="inner-main-abt-cont" data-aos="fade-right" data-aos-duration="1000">
                            <h1>Our Mission</h1>
                            <p>It is the mission of The Montgomery Fire Department to preserve life and property, promote public safety and fire prevention through leadership, management and actions, as an all risk life safety response provider. It is the department's endeavor to deliver the highest level of service to our residents with the utmost professionalism.
                                 </p>
                            <br>
                            <p>We are all volunteer and have been active and dedicated to our community since 1810. We're the oldest volunteer fire department in Orange County, having been organized on March 6th, 1810 with the appointment of the first three village fire wardens. We protect the residents of the Village of Montgomery as well as portions of the Town of Montgomery, totaling almost 17,000 citizens.</p>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-5 col-sm-5 col-xs-12 col-12 about-content abt-left">
                        <div class="inner-main-abt-cont" data-aos="fade-left" data-aos-duration="1000">
                            <div class="abt-img-holder">
                                <img src="../assets/img/about.jpg" alt="about" class="img-fluid">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
</template>

<script>
export default {
    name : 'OurMission'
}
</script>

<style>

    /* about */

.main-about {
    background-color: #fff;
    position: relative;
}
.main-about:before {
    content: '';
    position: absolute;
    top: -4.2rem;
    left: 0;
    height: 5rem;
    width: 100%;
    background-color: #ffffff;
    clip-path: polygon(0 100%, 0 29%, 50% 80%, 100% 29%, 100% 100%);
}
.main-about .inner-about {
    display: flex;
    align-items: center;
}
.main-about .inner-about .about-content {
    overflow: hidden;
}
.main-about .inner-about .about-content .inner-main-abt-cont {
    
}
.main-about .inner-about .about-content:nth-child(2) {
    padding-right: 2rem;
}
.main-about .inner-about .about-content:nth-child(2) .inner-main-abt-cont {
    margin-top: 3.5rem;
}
.abt-img-holder {
    position: relative;
    z-index: 1;
}
.abt-img-holder:before {
    position: absolute;
    top: -1.5rem;
    left: 70%;
    height: 50%;
    width: 81%;
    background-color: #ff8401;
    content: '';
    z-index: -1;
}
.main-about .inner-about .about-content .inner-main-abt-cont h1 {
    font-size: clamp(4.2rem, 4.3vw, 2.4rem);
    position: relative;
    width: fit-content;
    font-weight: 800;
}
.main-about .inner-about .about-content .inner-main-abt-cont h1:before {
    content: '';
    position: absolute;
    top: 95%;
    left: 75%;
    height: 0.3rem;
    width: 50%;
    background-color: #ff8400;
    transform: translate(-50%, -50%);
}
.main-about .inner-about .about-content .inner-main-abt-cont p {
    font-weight: 300;
    font-size: 1.7rem;
    font-weight: 400;
}


</style>