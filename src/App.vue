<template>
  <nav-bar/>
    <router-view />
  <foot-bar/>
</template>

<script>
import NavBar from './components/NavBar.vue'
import FootBar from './components/FootBar.vue'
export default {
  components:{
    NavBar,
    FootBar
  }
}
</script>
<style>

</style>
