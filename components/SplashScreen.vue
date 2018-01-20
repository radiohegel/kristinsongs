<template>
  <section class="hero is-fullheight has-img-background">
    <div class="hero-body">
      <p class="title is-1 has-text-link">Kristin Erickson</p>
    </div>
  </section>
</template>

<script>
  export default {

    name: 'SplashScreen',
    data () {
      return {

      }
    }
  }
</script>

<style lang="sass" scoped>
  
  .has-img-background
    background: url('../assets/images/dummyphoto.jpg')
    background-position: center center
    background-repeat:  no-repeat
    background-attachment: fixed
    background-size:  cover

</style>