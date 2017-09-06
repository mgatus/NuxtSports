<template lang="html">
  <div class="contact">
    <Navigation />
    contact page
  </div>
</template>

<script>
import Navigation from '~/components/Navigation.vue'
export default {
  components: {
    Navigation
  }
}
</script>

<style lang="sass">
  @import https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css
</style>
<style lang="sass" src="bulma"></style>

<style lang="sass">
  @import './assets/sass/main.sass'
</style>

<style lang="sass">
  header.about-head
    background-color: #131836
    background-image: url("./../assets/img/bg.png")
    background-size: cover
    height: 16vh
    margin-bottom: 30px
</style>
