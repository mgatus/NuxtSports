<template lang="html">
  <div class="app-container">
    <header class="about-head">
      <div class="upper-container container">
        <div class="columns">
          <div class="column logo">
            <img src="./../assets/img/logo.png" alt="">
          </div>
          <Navigation />
        </div>
      </div>
    </header>
    <div class="container">
      <h1>About</h1>
        <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam lectus odio, molestie nec elementum sit amet, elementum a nulla. Nullam sed ex sed ante malesuada condimentum. Praesent id congue sem. Vivamus condimentum posuere placerat. Etiam sagittis non ipsum non mollis. Sed dictum tempor arcu, eget fringilla libero pulvinar et. Fusce lacus ligula, hendrerit in metus at, lobortis lobortis eros. Praesent tellus lorem, varius vitae maximus ut, blandit sit amet ligula.</p>
        <br>
        <p>  Nam gravida fermentum ligula, sit amet rhoncus urna volutpat ut. Curabitur sollicitudin velit ut suscipit convallis. Integer sit amet accumsan massa, id ornare augue. Mauris lacinia velit lectus, ac tincidunt turpis maximus vitae. Aliquam et tincidunt ligula. Sed eget justo eu nibh condimentum feugiat. Pellentesque accumsan dignissim lorem. Sed id maximus est. Vivamus aliquam lorem risus, at porta ante condimentum vel. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Curabitur placerat quam at commodo vulputate. Aenean augue massa, rutrum sed nunc nec, accumsan cursus ante. Nam suscipit arcu vel lobortis malesuada.</p><br>

        <p>  Nam gravida fermentum ligula, sit amet rhoncus urna volutpat ut. Curabitur sollicitudin velit ut suscipit convallis. Integer sit amet accumsan massa, id ornare augue. Mauris lacinia velit lectus, ac tincidunt turpis maximus vitae. Aliquam et tincidunt ligula. Sed eget justo eu nibh condimentum feugiat. Pellentesque accumsan dignissim lorem. Sed id maximus est. Vivamus aliquam lorem risus, at porta ante condimentum vel. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Curabitur placerat quam at commodo vulputate. Aenean augue massa, rutrum sed nunc nec, accumsan cursus ante. Nam suscipit arcu vel lobortis malesuada.</p>

    </div>
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
