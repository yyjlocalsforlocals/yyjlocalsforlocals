<template>
    <div>

        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-default">
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
                                <h1 class="display-3  text-white">Community Resources
                                </h1>                                
                                <p class="lead  text-white">Links to Local grocery stores, restaurants, beer/liquor and pharmacies doing delivery.</p>
                                
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-12 order-md-1">
                        <tabs fill class="flex-column flex-md-row ">
                            <card shadow>
                                <tab-pane title="Grocery Stores">
                                    <ul class="list-unstyled"> 
                                        <li><a href="#" class="btn btn-link text-primary">SaveOnFoods</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Walmart Grocery</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Thrifty Foods</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Real Canadian Superstore</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Spud.ca</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Instacart</a></li>
                                    </ul>
                                    <p class="description">Note: Demand for grocery delivery/pick-up is extremely 
                                        high and should be reserved for those unable to shop in-person.</p>
                                </tab-pane>

                                <tab-pane title="Restaurants">
                                    <p class="lead">EAT Magazine’s <a href="#" class="text-primary">guide to local restaurants</a>, with filters for deliver, take-out, and closed</p>
                                    <p class="lead">Tasting Victoria’s <a href="#" class="text-primary">list of local restaurants</a> offering delivery, take-out, and gift cards</p>
                                    <ul class="list-unstyled"> 
                                        <li><a href="#" class="btn btn-link text-primary">Skip the Dishes</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Door Dash</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Tutti</a></li>
                                    </ul>
                                </tab-pane>

                                <tab-pane title="Beer/Liquor">
                                    <p class="lead">Growing list of breweries offering delivery available on Vancouver is Awesome.</p>
                                    <ul class="list-unstyled"> 
                                        <li><a href="#" class="btn btn-link text-primary">Everything Wine</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Category 12 Brewing</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Driftwood Brewery</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Whistle Buoy Brewing</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Hoyne Brewing Company</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Moon Under Water</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Twa Dogs</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Ucluelet Brewing Co.</a> – Call 250-726-0499 to place a beer or food order.</li>
                                    </ul>
                                </tab-pane>
                                
                                <tab-pane title="Pharmacies">
                                    <ul class="list-unstyled"> 
                                        <li><a href="#" class="btn btn-link text-primary">Shoppers Drug Mart</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">London Drugs</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Quadra Village Pharmacy</a></li>
                                        <li><a href="#" class="btn btn-link text-primary">Thrifty Foods Pharmacy</a></li>
                                    </ul>
                                </tab-pane>
                            </card>
                        </tabs>
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
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
export default {
  name: "home",
  components: {
    Tabs,
    TabPane
  }
};
</script>
