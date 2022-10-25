<script setup>
import GuestLayout from "../layouts/GuestLayout.vue";
import BannerComponent from "../components/homepage/BannerComponent.vue";
import ExpertComponent from "../components/homepage/ExpertComponent.vue";
import LearnMoreComponent from "../components/homepage/LearnMoreComponent.vue";
import ShowCaseComponent from "../components/homepage/ShowCaseComponent.vue";
import SearchComponent from "../components/homepage/SearchComponent.vue";
import CorporateCapabilitiesComponent from "../components/homepage/CorporateCapabilitiesComponent.vue";
import BrandSliderComponent from "../components/homepage/BrandSliderComponent.vue";
</script>
<template>
  <GuestLayout>
    <banner-component></banner-component>
    <expert-component></expert-component>
    <learn-more-component></learn-more-component>
    <show-case-component></show-case-component>
    <search-component></search-component>
    <corporate-capabilities-component></corporate-capabilities-component>
    <brand-slider-component></brand-slider-component>
  </GuestLayout>
</template>
