<template lang="html">
  <header>
    <div class="upper-container container">
      <div class="columns">
        <div class="column logo">
          <img src="./../assets/img/logo.png" alt="">
        </div>
        <div class="column text-info">
          <nav class="is-right navbar">
            <ul>
              <li><router-link to="/">Home</router-link></li>
              <li><router-link to="about">Baseball</router-link></li>
              <li><router-link to="about">Ice Hockey</router-link></li>
              <li><router-link to="about">TableTennis</router-link></li>
              <li><router-link to="about">Contact Us</router-link></li>
            </ul>
          </nav>
        </div>
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
</template>



<style lang="sass">
  @import './assets/sass/header.sass'
</style>
