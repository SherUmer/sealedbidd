<template>
  <main class="main-content">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <slider msg="Welcome home !"/>
    <TopCategories />
    <TopServices />
    <BestOffers />
    <Testimonials />
    <FreeServices />
    <Featured />
    <TopProviders />
    <footerComponent />
  </main>
</template>

<script>
// @ is an alias to /src
import slider from '@/components/HomeComponents/slider.vue';
import TopCategories from '@/components/HomeComponents/TopCategories.vue';
import TopServices from '@/components/HomeComponents/TopServices.vue';
import BestOffers from '@/components/HomeComponents/BestOffers.vue';
import Testimonials from '@/components/HomeComponents/Testimonials.vue';
import FreeServices from '@/components/HomeComponents/FreeServices.vue';
import Featured from '@/components/HomeComponents/Featured.vue';
import TopProviders from '@/components/HomeComponents/TopProviders.vue';
import footerComponent from '@/components/IncludeComponents/footerComponent.vue';


export default {
  name: 'HomeView',
  components: {
    slider, TopCategories, TopServices, BestOffers, Testimonials, FreeServices, Featured, TopProviders,footerComponent
  }
}
</script>
