<template>
  <div>
    <Header />
    <nuxt-logo></nuxt-logo>
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from './Header.vue'
import Footer from './Footer.vue'

export default {
  components: {
    Header,
    Footer,
  }
}
</script>
