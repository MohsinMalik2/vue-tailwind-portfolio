<template>
    <header-banner/>
    <HeroComponent/>
    <image-sample/>
    <FAQ/>
    <testimonial-component/>
</template>

<script lang="ts">
import FAQ from "@/components/FAQ.vue";
import HeaderBanner from "@/components/HeaderBanner.vue";
import ImageSample from "@/components/ImageSample.vue";
import TestimonialComponent from "@/components/TestimonialComponent.vue";
import { defineComponent } from "vue";
import HeroComponent from '../components/HeroComponent.vue'

export default defineComponent({
  name: "HomeView",
  components:{
    HeroComponent,
    HeaderBanner,
    FAQ,
    ImageSample,
    TestimonialComponent
  }
});
</script>
