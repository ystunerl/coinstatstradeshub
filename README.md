/*======================================================
    Media Query
=======================================================*/

/* max-width 992px */
@media (max-width: 992px) {
    .padding{ padding: 60px 0; }
    .sm-padding{ padding: 15px; }
    p br{ display: none; }
    span br{ display: none; }

    .default-btn{ padding: 0 30px; }

    .section-heading h2{
        font-size: 32px;
        line-height: 42px;
    }
    .section-heading p br{
        display: inherit;
    }
    .contact-section .contact-form{margin-top: 0;}
    .contact-section .contact-form .form-group{margin-bottom: 0;}
    .contact-section .contact-form .form-control.address {
        height: inherit;
        margin: 15px 0 20px;
    }
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .padding{ padding: 60px 0; }
    .xs-padding{ padding: 15px; }
    .section-heading p br,
    p br{ display: none; }
    .team-items{
        overflow: hidden;
    }
}

/* max-width 580px */
@media all and (max-width: 580px) {
    #scrollup {
        bottom: 20px;
        right: 20px;
    }
    .header-1 .header-right a.header-btn {
        padding: 0 15px;
        font-size: 8px;
    }
    .about-section .play-btn {
        top: 45%;
    }
    .about-bg-holder .bg-front {
        right: 0px;
        top: 50px;
    }
    .contact-section .contact-form{
        padding: 35px;
    }
    .contact-section .form-heading h3 {
        font-size: 30px;
        line-height: 1.2;
    }
}

@media (max-width: 320px){
    .header-1 .header-right a.header-btn{ display: none; }
}

/*======================================================
    Main Slider
=======================================================*/

/* max-width 768px */
@media all and (max-width: 768px) {
    .slider-content-wrap{ height: 500px; }
    .main-slider .slide-caption.big {
        font-size: 32px;
        line-height: 22px;
        min-height: 30px;
    }
    .main-slider .slide-caption.small{ font-size: 14px; }
    .main-slider .slide-caption.big .inner-layer{
        line-height: 40px;
        margin-top: 0;
    }
    .main-slider .slide-caption.small{margin-top: 0;}
    .border-layers {
        width: 200px;
        height: 290px;
        left: 60px;
        top: 110px;
    }
    .slider-content{
        margin: 0 20px;
    }
    .main-slider .slick-arrow{
        width: 30px;
    }
}

/* max-width 580px */
@media all and (max-width: 580px) {}

/* max-width 420px */
@media all and (max-width: 420px) {
    .border-layers{ display: none; }
    .construction .slider-content {
        margin-left: 20px;
    }
}
@media all and (max-width: 380px) {
    .slider-content-wrap {
        height: 450px;
    }
    .main-slider .slide-caption.medium{
        line-height: 1;
    }
    .main-slider .slide-caption.big {
        font-size: 22px;
        line-height: 22px;
        letter-spacing: 0;
    }
    .main-slider .slide-caption.big .inner-layer {
        line-height: 1.2;
    }
    .main-slider .slide-btn-group {
        margin-top: 15px;
    }
}

/*======================================================
    Hero Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px){
    .agency .hero-section br{ display: inherit; }
    .saas .hero-section br{ display: inherit; }
    .hero-img-2{ background-size: 80%; }

    .saas .hero-img{
        right: -200px;
        -webkit-background-size: 70%;
        background-size: 70%;
    }

    .saas .hero-section{ height: 500px; }
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .agency .hero-section{
        height: 450px;
        border-bottom: 1px solid #f1f1f1;
    }
    .hero-img-2{ display: none; }
    .agency .hero-content h1{
        font-size: 36px;
        line-height: 1.2;
    }
    .saas .hero-img{display: none;}
    .saas .hero-content h2{ font-size: 32px;}
    .saas .content-section .section-heading{ text-align: left; }
}

/* max-width 580px */
@media all and (max-width: 580px) {
    .saas .hero-section {
        height: 400px;
    }
    .subscribe-section .subscribe-form {
        flex-direction: column;
        width: 100%;
    }
    .subscribe-section .subscribe-form .submit {
        position: inherit;
        right: inherit;
        top: inherit;
        transform: inherit;
        cursor: pointer;
        width: 100%;
        margin-top: 15px;
        height: 55px;
        line-height: 55px;
    }
    .agency .hero-content p br,
    .agency .hero-content h1 br{ display: none; }
}

/* max-width 420px */
@media all and (max-width: 420px) {
    .saas .hero-content h2 {
        line-height: 1.2;
    }
    .saas .hero-content p br,
    .saas .hero-content h2 br{
        display: none;
    }
}

/* max-width 320px */
@media (max-width: 320px) {}


/*======================================================
    About Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px){
    .about-section .section-heading h2{
        font-size: 28px;
        line-height: 36px;
    }
    .about-bg-holder{}
    .about-bg-holder .dot-pattern{
        right: 80px;
        top: 60px;
    }
    .about-bg-holder .bg-back{ top: 100px; }
    .about-section .play-btn {
        right: 130px;
        top: 190px;
    }
    .about-section .default-btn{margin-right: 0;}
    .about-section .btn-wrap img{
        max-width: 150px;
        margin-left: 10px;
    }
    .about-section-3 .about-bg-holder{
        right: 0;
        margin-top: 50px;
    }
    .agency .address-box{ margin-top: 50px; }
    .agency .appointment-form{ padding-right: 0; }
    .services-wrap .sm-padding{
        padding: 20px 15px;
    }
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .about-bg-holder {
        height: 400px;
        right: 0;
        margin-top: 40px;
    }
    .about-bg-holder .bg-front {
        display: none;
    }
    .about-bg-holder .bg-back {
        top: 0;
        width: 100%;
        height: 100%;
        background-size: 100%;
        background-position: center center;
    }
    .about-section .play-btn {
        right: 50%;
        top: 50%;
        transform: translate(50%, -50%);
    }
    .construction .about-bg-holder{
        right: auto;
        margin-top: 40px;
        height: auto;
    }
    .construction .about-bg-holder .about-bg{
        display: none;
    }
    .construction .about-bg-holder img {
        width: 100%;
    }
    .construction .about-bg-holder .play-btn{
        margin-right: 0;
    }
}

/* max-width 580px */
@media all and (max-width: 580px) {
    .services-wrap .sm-padding{ padding: 15px; }
    .services-wrap .sm-padding:not(:last-of-type){
        margin-bottom: 20px;
    }
}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}


/*======================================================
    Content Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px){
    .construction .content-wrap .text-right{
        text-align: center!important;
    }
    .saas .content-section .section-heading{margin-bottom: 40px;}
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .content-section .col-lg-6{
        text-align: center!important;
    }
    .content-section .content-bg{ margin-top: 50px; }
}

/* max-width 580px */
@media all and (max-width: 580px) {}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}

/*======================================================
    Service / Feature Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px){
    .saas .feature-items .col-md-6:nth-child(4),
    .saas .feature-items .col-md-6:nth-child(2) {
        transform: translateY(0);
    }
}

/* max-width 768px */
@media all and (max-width: 768px) {}

/* max-width 580px */
@media all and (max-width: 580px) {}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}


/*======================================================
    Appointment Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px){
    .appointment-form{
        position: inherit;
        margin-top: 20px;
        top: 0;
    }
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .appointment-form .form-group{
        margin-bottom: 0;

    }
    .appointment-form .form-group .col-md-12,
    .appointment-form .form-group .col-sm-6{
        padding: .5rem;
    }
    .appointment-form .default-btn{ margin-top: .5rem; }
}

/* max-width 580px */
@media all and (max-width: 580px) {}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}

/*======================================================
    CTA Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px){
    .cta-content{
        padding: 100px 0;
    }
    .cta-img {
        right: -110px;
    }
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .cta-content h2{ font-size: 32px; }
}

/* max-width 580px */
@media all and (max-width: 580px) {}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}

/*======================================================
    Team Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px){
    .team-section-2 .team-items .custom-col{}
    .team-section-2 .team-social li a{
        width: 25px;
        height: 25px;
        line-height: 25px;
    }
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .team-section-2 .team-item img{ width: 100%; }
    .team-section-2 .team-items{
        grid-template-columns: 50% 50%;
        grid-row-gap: 30px;
    }
    .team-section-2 .team-items .custom-col:nth-child(2n+2){
        margin-top: 0;
    }
}

/* max-width 580px */
@media all and (max-width: 580px) {
    .team-section-2 .team-items{
        grid-template-columns: 100%;
    }
}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}

/*======================================================
    Portfolio Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px) {
    .project-details{
        padding: 0;
        margin-top: 50px;
    }
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .portfolio-filter li {
        margin: 0 8px;
    }
    .project-details-meta h3{ font-size: 16px;}
}

/* max-width 580px */
@media all and (max-width: 580px) {}

/* max-width 420px */
@media all and (max-width: 420px) {
    .project-details .btn-group{
        flex-direction: column;
        justify-content: inherit;
    }
    .project-details .btn-group .default-btn {
        margin-right: auto;
    }
    .project-details .social-share {
        margin-right: auto;
        margin-top: 20px;
    }
    .project-details .social-share li a {
        margin-left: 0;
        margin-right: 5px;
    }
}

/* max-width 320px */
@media (max-width: 320px) {}

/*======================================================
    Skill Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px) {}

/* max-width 768px */
@media all and (max-width: 768px) {
    .skill-wrap{ padding: 60px; }
}

/* max-width 580px */
@media all and (max-width: 580px) {}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}


/*======================================================
    Counter Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px) {
    .counter-wrap{ box-shadow: none; }
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .counter-wrap{ padding: 40px 0; }
}

/* max-width 580px */
@media all and (max-width: 580px) {}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}

/*======================================================
    Testimonial Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px) {
    .saas .testi-controls{display: none;}
    .saas .testimonial-section .section-heading{ text-align: center; }
    .carousel-wrap:before{
        left: 70px;
        background-size: 70%;
    }
}

/* max-width 768px */
@media all and (max-width: 768px) {}

/* max-width 580px */
@media all and (max-width: 580px) {
    .testimonial-section-2 .testi-item {
        display: block;
        padding: 20px;
    }
    .testimonial-section-2 .testi-item .review-content {
        margin-left: 0;
    }
    .testimonial-section-2 .testi-item img {
        margin-bottom: 15px;
    }
}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}

/*======================================================
    Pricing Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px) {
    .saas .pricing-section .section-heading{ text-align: center; }
    .cd-pricing-switcher{text-align: center;}
}

/* max-width 768px */
@media all and (max-width: 768px) {}

/* max-width 580px */
@media all and (max-width: 580px) {}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}

/*======================================================
    Blog Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px) {
    .sidebar-wrap {
        padding-left: 0;
        margin-top: 20px;
    }
}

/* max-width 768px */
@media all and (max-width: 768px) {
    .sidebar-wrap{ padding-left: 0; }
    .blog-single-content h2 a{
        font-size: 22px;
        line-height: 28px;
    }
    .blog-single-content h2{ line-height: 28px; }
    blockquote p{
        font-size: 20px;
        line-height: 32px;
    }
    .classic-blog .blog-content h3 a{
        font-size: 22px;
        line-height: 30px;
    }
    .page-content h2 {
        font-size: 30px;
        line-height: 36px;
    }
}

/* max-width 580px */
@media all and (max-width: 580px) {
    section{ overflow: hidden; }
    .author-box {
        flex-direction: column;
    }
    .author-box img {
        margin-right: auto;
        margin-bottom: 15px;
    }
    .author-info {
        padding-left: 0;
    }
    .skill-wrap {
        padding: 50px 15px;
    }
    .cta-content h2 {
        font-size: 28px;
        line-height: 1.3;
    }
    .section-heading h2 br,
    .cta-content h2 br{ display: none; }
    .corporate .footer-top{ padding: 60px 0; }
    .appointment-form {
        padding: 40px 20px;
    }
    .appointment-form h2 {
        font-size: 28px;
        line-height: 1.3;
    }
    .carousel-wrap {
        padding: 30px 0 50px;
    }
    .testi-item .review{ padding: 20px; }
    .carousel-wrap:before {
        left: -48px;
        background-size: 100%;
    }
    .carousel-wrap:before {
        background-position: center center;
        background-size: 100%;
        width: 120%;
        left: -48px;
        top: -110px;
    }
    .testimonials-carousel-3 .testi-item .review p {
        font-size: 20px;
    }
    .testimonial-section-2 .testi-item .testi-content h4 {
        margin-top: 0;
    }
    .footer-section-inner {
        padding: 60px 0;
    }
    .agency .hero-section {
        height: 400px;
    }
    .agency .hero-content h1 {
        font-size: 28px;
        line-height: 1.3;
    }
    .hero-content .default-btn{
        padding: 0 20px;
    }
    .hero-content .default-btn,
    .hero-content .play-btn small{
        font-size: 10px;
    }
}

/* max-width 420px */
@media all and (max-width: 420px) {
    .page-content h2 br{ display: none; }
    .page-header{
        height: 320px;
        padding: 0;
    }
    .padding {
        padding: 40px 0;
    }
    .blog .blog-section.padding {
        padding-bottom: 90px;
    }
    .blog-content {
        padding: 25px;
    }
    .footer-section.info-active{
        /* margin-top: 57px; */
    }
    .agency .footer-section.info-active{
        margin-top: 0;
    }
    .blog-single-wrap .comments-area li > div{ padding: 20px; }
    .blog-single-wrap .comments-area .comment-thumb { left: 20px; }
    .blog-single-wrap .comments-area .comment-thumb .comment-img {
        width: 60px;
        height: 60px;
    }
    .blog-single-wrap .comments-area .comment-main-area { padding-left: 75px; }
    .blog-single-wrap .comments-area ol ul { padding-left: 20px; }
    .blog-single-wrap .comment-respond .form-inputs > input:nth-child(2),
    .blog-single-wrap .comment-respond .form-inputs > input:nth-child(3) {
        width: 100%;
    }
    .business .about-section .default-btn {
        margin-right: 0;
        padding: 0 15px;
    }
}

/* max-width 320px */
@media (max-width: 320px) {
    .blog-single-wrap .comments-area li > div { padding: 20px 10px; }
    .blog-single-wrap .comments-area .comment-thumb { left: 10px; }
    .blog-single-wrap .comments-area .comment-thumb .comment-img {
        width: 50px;
        height: 50px;
    }
    .blog-single-wrap .comments-area .comment-main-area { padding-left: 65px; }
    .blog-single-wrap .comments-area ol ul { padding-left: 10px; }
    .blog-single-wrap .comments-area .comments-meta h4{
        font-size: 16px;
        letter-spacing: 0;
        line-height: 1.3;
    }
    .blog-single-wrap .comments-area .comments-meta h4 span {
        font-weight: 400;
        display: block;
        font-size: 10px;
        margin-left: 0;
    }
    .blog-single-wrap .comments-area .comment-main-area p {
        margin-bottom: 20px;
        font-size: 13px;
        line-height: 1.6;
    }
    blockquote {
        padding: 30px;
    }
    blockquote p {
        font-size: 18px;
        line-height: 1.5;
        margin-bottom: 0;
    }
    blockquote span {
        margin-top: 10px;
    }
    .contact-section .contact-form {
        padding: 20px;
    }
    .contact-form .col-md-12,
    .contact-form .sm-padding{
        padding: 10px;
    }
}

/*======================================================
    Footer Section
=======================================================*/
/* max-width 1024px */
@media (max-width: 1024px) {}

/* max-width 992px */
@media (max-width: 992px){

    .footer-top{ padding: 60px 0; }
    .footer-top.active{ padding: 100px 0 60px; }
    .footer-widget.link-widget{ margin-left: 0; }
    .footer-info-list{ padding: 20px; }
    .footer-info-list svg {
        width: 30px;
        margin-right: 10px;
    }
    .footer-info-list h3 {
        font-size: 12px;
        letter-spacing: 0;
    }
}
/* max-width 768px */
@media all and (max-width: 768px) {
    .footer-info-list{
        width: 100%;
    }
    .section-heading h2 {
        font-size: 28px;
        line-height: 36px;
    }
    .footer-info-inner{
        flex-wrap: wrap;
    }
    .footer-info-inner .footer-info-list:not(:last-of-type) {
        border-right: none;
        border-bottom: 1px solid rgba(255,255,255,0.5);
    }
    .footer-widget.link-widget{ margin-left: 0; }
    .info-active .footer-top {
        padding: 220px 0 60px;
    }
    .footer-top{ padding: 100px 0; }
    .footer-info-list{ justify-content: flex-start; }
    .sponsor-item {
        padding: 0 25px;
    }
    .footer-cta{
        position: inherit;
    }
    .footer-cta-inner{
        width: 100%;
        padding: 20px;
    }
    .footer-cta-inner .footer-cta-list h2 {
        font-size: 22px;
        line-height: 28px;
    }
    .footer-top.active {
        padding: 0 0 60px;
    }
}

/* max-width 580px */
@media all and (max-width: 580px) {
    .footer-cta-inner{
        flex-direction: column;
        text-align: center;
    }
    .footer-cta-inner .default-btn{
        margin-top: 20px;
    }
}

/* max-width 420px */
@media all and (max-width: 420px) {}

/* max-width 320px */
@media (max-width: 320px) {}
