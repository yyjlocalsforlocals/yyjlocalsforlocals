<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <img src="img/brand/white.png" alt="logo">
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/">
                        <img src="img/brand/blue.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <base-dropdown class="nav-item" menu-classes="dropdown-menu-xl">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-ui-04 d-lg-none"></i>
                        <span class="nav-link-inner--text">Community Resources</span>
                    </a>
                    <div class="dropdown-menu-inner">
                        <router-link to="/localdelivery"
                        
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-primary rounded-circle text-white">
                                <i class="ni ni-delivery-fast"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="heading text-primary mb-md-1">Local Delivery</h6>
                                <p class="description d-none d-md-inline-block mb-0">Links to Local
                                    grocery stores, restaurants, beer/liquor and pharmacies doing delivery.</p>
                            </div>
                        </router-link>
                        <a href="https://tastingvictoria.com/restaurants"
                           class="media d-flex align-items-center"
                           target="_blanks"
                           rel="noopener">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <i class="ni ni-shop"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">What's Open (Tasting Victoria)</h5>
                                <p class="description d-none d-md-inline-block mb-0">Who's delivering, who's doing pick up, 
                                    and who's offering gift cards in the YYJ food scene.</p>
                            </div>
                        </a>
                        <router-link to="/covidinformation"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-success rounded-circle text-white">
                                <i class="ni ni-single-copy-04"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-success mb-md-1">COVID-19 Information</h5>
                                <p class="description d-none d-md-inline-block mb-0">Resources collected
                                    from around the internet.</p>
                            </div>
                        </router-link>
                    </div>
                </base-dropdown>
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.facebook.com/YYJLocalsForLocals/" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="Like us on Facebook">
                        <i class="fa fa-facebook-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Facebook</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.instagram.com/yyjlocalsforlocals/"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Follow us on Instagram">
                        <i class="fa fa-instagram"></i>
                        <span class="nav-link-inner--text d-lg-none">Instagram</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://twitter.com/yyjlocal4local" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="Follow us on Twitter">
                        <i class="fa fa-twitter-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Twitter</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://join.slack.com/t/yyjlocalsforlocals/shared_invite/zt-cwgar2l3-d2fr_8Jj62nrOCkR6_3Vhg"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Join us on Slack">
                        <i class="fa fa-slack"></i>
                        <span class="nav-link-inner--text d-lg-none">Slack</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
