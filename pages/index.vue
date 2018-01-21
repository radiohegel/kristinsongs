<template>
	<div>
	  <splash-screen/>
	  <about-section/>
	</div>
</template>

<script>
  import SplashScreen from '../components/SplashScreen.vue'
  import AboutSection from '../components/AboutSection.vue'

  export default {
    components: { SplashScreen, AboutSection }
  }
</script>

<style lang="sass">

</style>
