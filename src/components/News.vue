<template>
    <section class="news">
            <div class="container">
                <div class="new-main-heading text-center">
                    <h1>News <span class="color-red">&</span> Events</h1>
                </div>
                <div class="row">
                    <div class="col-md-6">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="inner-news-cont">
                                    <div class="news-img">
                                        <img src="../assets/img/news-1.jpg" alt="news">
                                    </div>
                                    <div class="news-headline">
                                        <h2>Road Closed, House on Fire</h2>
                                        <div class="date">
                                            <i class="fa-solid fa-calendar"></i> <span>Aug 25, 2020</span>
                                        </div>
                                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod quos explicabo</p>
                                    </div>
                                    <div class="readmore-btn">
                                        <a href="#">Read More</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="inner-news-cont">
                                    <div class="news-img">
                                        <img src="../assets/img/new-2.jpg" alt="news">
                                    </div>
                                    <div class="news-headline">
                                        <h2>Shoe Factory Caught Fire</h2>
                                        <div class="date">
                                            <i class="fa-solid fa-calendar"></i> <span>Oct 14, 2020</span>
                                        </div>
                                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod quos explicabo</p>
                                    </div>
                                    <div class="readmore-btn">
                                        <a href="#">Read More</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="inner-news-cont">
                            <div class="new-right-section">
                                <div class="date-alert">
                                    <p>18<br><span>Oct</span></p>
                                </div>
                                <div class="fire-event-update">
                                    <div class="news-headline">
                                        <h2>Emergency Medical Services Tips</h2>
                                        <div class="date">
                                            <i class="fa-solid fa-location-dot color-red"></i><span>Glasgow, DO4 89GR</span> -&nbsp; <i class="fa-regular t fa-clock color-red"></i> <span>03:00 pm - 10:00 pm</span>
                                        </div>
                                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci necessitatibus voluptatibus neque mollitia optio tempore consequuntur unde quo, voluptatem odit ab nihil porro nisi. Temporibus repudiandae fugiat eaque quos illum.</p>
                                    </div>
                                    <div class="readmore-btn">
                                        <a href="#">Read More</a>
                                    </div>
                                </div>
                            </div>
                            <div class="new-right-section">
                                <div class="date-alert">
                                    <p>21<br><span>Oct</span></p>
                                </div>
                                <div class="fire-event-update">
                                    <div class="news-headline">
                                        <h2>Emergency Medical Services Tips</h2>
                                        <div class="date">
                                            <i class="fa-solid fa-location-dot color-red"></i><span>Glasgow, DO4 89GR</span> -&nbsp; <i class="fa-regular t fa-clock color-red"></i> <span>03:00 pm - 10:00 pm</span>
                                        </div>
                                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci necessitatibus voluptatibus neque mollitia optio tempore consequuntur unde quo, voluptatem odit ab nihil porro nisi. Temporibus repudiandae fugiat eaque quos illum.</p>
                                    </div>
                                    <div class="readmore-btn">
                                        <a href="#">Read More</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
</template>

<script>
export default {
    name : 'NewsMedia'
}
</script>

<style>

.news {
    padding-bottom: 0;
    background-color: #fff;
}
.news .new-main-heading {}
.news .new-main-heading h1 {
    padding-bottom: 2.5rem;
    font-size: 5rem;
    font-weight: 800;
}
.news .inner-news-cont {
    padding-bottom: 1.5rem;
    font-family: 'Poppins';
    padding: 0rem 1rem;
}
.news .inner-news-cont .date {
    font-size: 1.3rem;
    color: #000;
    padding: 1rem 0;
}
.news .inner-news-cont .date i {
}
.news .inner-news-cont .date span {
    padding-left: 0.5rem;
}
.news .inner-news-cont .news-img {
    padding-bottom: 2rem;
}
.news .inner-news-cont .news-img img {}
.news .inner-news-cont .news-headline {}
.news .inner-news-cont .news-headline h2 {
    font-weight: 500;
    font-size: 1.7rem;
    font-family: 'Roboto', sans-serif;
}
.news .inner-news-cont .news-headline p {
    padding-bottom: 3rem;
    font-size: 1.7rem;
}
.news .inner-news-cont .readmore-btn {
    position: relative;
    display: flex;
    justify-content: flex-end;
    overflow: hidden;
    z-index: 33333;
}
.news .inner-news-cont .readmore-btn:before {
    content: '';
    position: absolute;
    height: 0.1rem;
    width: 100%;
    background-color: #bbbbbb;
    top: 50%;
    left: 0;
    /* border-top: 0.3rem solid #ddd; */
    transform: inherit;
    z-index: -1;
}
.news .inner-news-cont .readmore-btn a {
    text-decoration: none;
    color: #403939;
    font-size: 1.25rem;
    display: inline-block;
    width: 9rem;
    text-align: center;
    background-color: #fff;
}
.news .inner-news-cont .new-right-section {
    display: flex;
    gap: 2rem;
}
.news .inner-news-cont .new-right-section:nth-child(2) {
    padding-top: 3rem;
    border-top: 0.1rem solid #ddd;
    margin-top: 3rem;
}
.news .inner-news-cont .new-right-section .date-alert {
    text-align: center;
    width: 20%;
}
.news .inner-news-cont .new-right-section .date-alert p {
    background-color: #f01313;
    color: #fff;
    padding: 2.2rem;
    font-size: 3rem;
    font-weight: 700;
    line-height: 0.8;
}
.news .inner-news-cont .new-right-section .readmore-btn {
    display: block;
                                                        }
.news .inner-news-cont .new-right-section .readmore-btn a {
    text-align: left;
}
.news .inner-news-cont .new-right-section .readmore-btn:before {
    content: '';
    position: absolute;                                                                                                                                                height: 0;}
.news .inner-news-cont .new-right-section .date-alert p span {
    font-size: 1.7rem;
    font-weight: 500;
}


</style>