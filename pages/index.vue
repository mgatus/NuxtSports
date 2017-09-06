<template>
  <div class="app-container">
    <header class="home-head">
      <div class="upper-container container">
        <div class="columns">
          <div class="column logo">
            <img src="./../assets/img/logo.png" alt="">
          </div>
          <Navigation />
        </div>
      </div>

      <div class="container tagline">
          <h1><span class="upp">BE RECRUITED</span></h1>
          <h1><span class="low push-right">PLAY COLLEGE SPORTS</span></h1>
          <hr class="hardline" />
      </div>
      <div class="button-app">
        <router-link class="button is-primary" to="/"><i class="fa fa-apple" aria-hidden="true"></i> App Store</router-link>
        <router-link class="button is-primary" to="about"><i class="fa fa-play" aria-hidden="true"></i> Google Play</router-link>
      </div>
    </header>

    <Players />

  </div>
</template>

<script>
import Navigation from '~/components/Navigation.vue'
import Players from '~/components/Players.vue'

export default {
  components: {
    Navigation,
    Players
  }
}
</script>

<style lang="css">
  @import './../node_modules/font-awesome/css/font-awesome.min.css';
</style>

<style lang="sass" src="bulma"></style>

<style lang="sass">
  @import './assets/sass/main.sass'
</style>
