<template>
    <div>

        <hero></hero>
        <!--
        <div class="position-relative">
            

            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-default shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-8">
                                <h1 class="display-3  text-white">YYJ Small Business
                                    <span>+</span>
                                    <span>Tech & Marketing Volunteers</span>
                                </h1>
                                <p class="lead  text-white">YYJLocalsForLocals is a group of community-minded 
                                    tech and marketing professionals offering pro-bono assistance to local small 
                                    businesses, restaurants, and bars.</p>
                                <div class="btn-wrapper">
                                    <base-button tag="a"
                                                 href="https://www.creative-tim.com/product/argon-design-system"
                                                 class="mb-3 mb-sm-0"
                                                 type="white"
                                                 target="_blank">
                                                <span class="nav-link-inner--text">
                                                    I would like assistance 
                                                </span>
                                                <span class="btn-inner--icon">
                                                    <i class="fa fa-external-link" aria-hidden="true"></i>
                                                </span>                                        
                                    </base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

        </div>-->
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">
                        <div class="card bg-default shadow border-0">
                            <img v-lazy="'img/theme/img-4-2.jpg'" class="card-img-top">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                     class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="fill-default"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-default"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">I'm a small business owner</h4>
                                <p class="lead text-italic text-white">I would like a pro-bono website, marketing planning or promotional materials.</p>
                                <base-button tag="a" href="https://docs.google.com/forms/d/e/1FAIpQLSev1kevBOZtyN0ZCnBvy3gfEDDasZBd-Ykr811eFaocji949w/viewform"
                                             type="white" block size="lg" target="_blank">
                                    <span class="nav-link-inner--text">
                                        I would like assistance
                                    </span>
                                    <span class="btn-inner--icon">
                                        <i class="fa fa-external-link" aria-hidden="true"></i>
                                    </span>  
                                </base-button> 
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <h3>Pro-Bono Services We Can Offer You</h3>
                            <p>I would like a pro-bono website, marketing planning or promotional materials.</p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-hat-3"></badge>
                                        <h6 class="mb-0">Help designing merch to drive sales</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-laptop"></badge>
                                        <h6 class="mb-0">Building a single page website (landing page)</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-shop"></badge>
                                        <h6 class="mb-0">Write a message about how your business is handling COVID-19</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-email-83"></badge>
                                        <h6 class="mb-0">Email design to send to your customers</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-mobile-button"></badge>
                                        <h6 class="mb-0">Social media post or ad copy and design</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-credit-card"></badge>
                                        <h6 class="mb-0">Help setting up gift card sales on your website</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-delivery-fast"></badge>
                                        <h6 class="mb-0">Marketing help to promote your delivery service</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-box-2"></badge>
                                        <h6 class="mb-0">Help setting up a subscription box service</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-0">
            <div class="container">
                <card gradient="warning"
                      no-body
                      shadow-size="lg"
                      class="border-0">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">A Victoria COVID-19 Project.</h3>
                                <p class="lead text-white mt-3">YYJLocalsForLocals is a group of community-minded 
                                    tech and marketing professionals offering pro-bono assistance to local small 
                                    businesses, restaurants, and bars.</p>
                            </div>
                            <div class="col-lg-4 ml-lg-auto">
                                <base-button tag="a" href="https://www.creative-tim.com/product/vue-argon-design-system"
                                             type="white" block size="lg">
                                    I would like to volunteer
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>
        <section class="section section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-1 bg-gradient-warning shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container py-0">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-lg-2 ml-lg-auto">
                        <div class="position-relative pl-md-5">
                            <img src="img/ill/ill-2.svg" class="img-center img-fluid">
                        </div>
                    </div>
                    <div class="col-lg-6 order-lg-1">
                        <div class="d-flex px-3">
                            <div>
                                <icon name="ni ni-building" size="lg" class="bg-gradient-white" color="primary" shadow
                                      rounded></icon>
                            </div>
                            <div class="pl-4">
                                <h4 class="display-3 text-white">Modern Interface</h4>
                                <p class="text-white">The Arctic Ocean freezes every winter and much of the sea-ice then
                                    thaws every summer, and that process will continue whatever happens.</p>
                            </div>
                        </div>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">Awesome Support</h5>
                                    <p>The Arctic Ocean freezes every winter and much of the sea-ice then thaws
                                        every summer, and that process will continue whatever happens.</p>
                                    <a href="#" class="text-success">Learn more</a>
                                </div>
                            </div>
                        </card>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-active-40" gradient="warning" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-warning">Modular Components</h5>
                                    <p>The Arctic Ocean freezes every winter and much of the sea-ice then thaws
                                        every summer, and that process will continue whatever happens.</p>
                                    <a href="#" class="text-warning">Learn more</a>
                                </div>
                            </div>
                        </card>
                    </div>
                </div>
            </div>
        </section><!--
        <section class="section section-lg pt-lg-0 ">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-primary text-uppercase">Download Argon</h6>
                                    <p class="description mt-3">Argon is a great free UI package based on Bootstrap 4
                                        that includes the most important components and features.</p>
                                    <div>
                                        <badge type="primary" rounded>design</badge>
                                        <badge type="primary" rounded>system</badge>
                                        <badge type="primary" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="primary" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-success text-uppercase">Build Something</h6>
                                    <p class="description mt-3">Argon is a great free UI package based on Bootstrap
                                        4 that includes the most important components and features.</p>
                                    <div>
                                        <badge type="success" rounded>business</badge>
                                        <badge type="success" rounded>vision</badge>
                                        <badge type="success" rounded>success</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="success" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-planet" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">Prepare Launch</h6>
                                    <p class="description mt-3">Argon is a great free UI package based on Bootstrap
                                        4 that includes the most important components and features.</p>
                                    <div>
                                        <badge type="warning" rounded>marketing</badge>
                                        <badge type="warning" rounded>product</badge>
                                        <badge type="warning" rounded>launch</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="warning" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>-->
        <section class="section bg-secondary">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div class="card bg-default shadow border-0">
                            <img v-lazy="'img/theme/img-1.jpg'" class="card-img-top">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                     class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="fill-default"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-default"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">About Us</h4>
                                <p class="lead text-italic text-white">The four organizers behind the project, Emily Hannan, Eve Olynyk, Tara Price, and 
                                Nathan Sorochan, have assembled a team of volunteers to support local businesses during the COVID-19 crisis. </p>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <icon name="ni ni-settings" class="mb-5" size="lg" type="warning" shadow rounded></icon>

                            <h3>Our purpose</h3>
                            <p class="lead">
                                Victoria is such a great place to live because of the 
                                    amazing restaurants, bars, breweries, coffee shops, and quaint little stores. When this 
                                    is over and everyone is safe and healthy, we want these places to still be around.
                                </p>
                            <p>To get work out quickly, YYJLocalsForLocals offers eight main services, listed above. Any small business in the 
                                area can request one of these services through the website located at yyjlocalsforlocals.com.</p>
                            <a href="#" class="font-weight-bold text-warning mt-5">A beautiful UI Kit for impactful
                                websites</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">Volunteer Support is provided by these great organisations & groups</h2>
                    </div>
                </div>
                <div class="row row-grid mt-5">
                    <div class="col-lg-4">
                        <icon name="ni ni-settings" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h4 class="text-white mt-3">YYJTECH</h4>
                        <p class="text-white mt-3">Slack group for the Tech Industry in Victoria.</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-ruler-pencil" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h4 class="text-white mt-3">YYJTECH Ladies</h4>
                        <p class="text-white mt-3">Slack group for Ladies in Tech in Victoria</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-atom" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h4 class="text-white mt-3"></h4>
                        <p class="text-white mt-3">Want to help or be listed here? Email.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Want to contact us?</h4>
                            <p class="mt-0">Your contributions are very important to the community.</p>
                            <base-input class="mt-5"
                                        alternative
                                        placeholder="Your name"
                                        addon-left-icon="ni ni-user-run">
                            </base-input>
                            <base-input alternative
                                        placeholder="Email address"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                              cols="80" placeholder="Type a message..."></textarea>
                            </base-input>
                            <base-button type="default" round block size="lg">
                                Send Message
                            </base-button>
                        </card>
                    </div>
                </div>
            </div>
        </section>

    </div>
</template>

<script>

import Hero from "./components/Hero";
export default {
  name: "home",
  components: {Hero}
};
</script>
