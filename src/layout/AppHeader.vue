<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <div class="name">Maró Hajnalka</div>
                <div class="position">Webfejlesztő</div>
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                        <div class="name">Maró Hajnalka</div>
                        <div class="position">Webfejlesztő</div>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                    <a slot="title" href="#" class="nav-link" role="button">
                        <span class="nav-link-inner--text">Munkáim</span>
                    </a>
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <span class="nav-link-inner--text">Rólam mondták</span>
                    </a>
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <span class="nav-link-inner--text">Elérhetőség</span>
                    </a>
            </ul>
            
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton
  }
};
</script>
<style>
</style>
