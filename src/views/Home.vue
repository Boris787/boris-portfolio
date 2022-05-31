<template>
  <div class="home">
    <Header />
    <Section />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Contact from '../components/sections/Contact.vue'
import Footer from '../components/sections/Footer.vue'
import Header from '../components/sections/Header.vue'
import Section from '../components/sections/Section.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Section,
    Contact,
    Footer
  }
}
</script>
