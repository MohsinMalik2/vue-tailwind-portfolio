<template>
  <about-image/>
  <about-component/>
  <cta-component/>
  <feature-component/>
</template>

<script>
import CtaComponent from '@/components/CtaComponent.vue'
import AboutComponent from "../components/AboutComponent.vue"
import FeatureComponent from '@/components/FeatureComponent.vue'
import AboutImage from '@/components/AboutImage.vue'
export default {
  components: { AboutComponent, CtaComponent,FeatureComponent, AboutImage },
}
    
</script>
