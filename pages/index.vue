<template>
  <div>
    <!-- <Navbar />
      <HeroSection />
      <FeaturesSection /> -->
    <Header />
    <Gallery />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Gallery from '@/components/Gallery.vue'
//   import FeaturesSection from '@/components/FeaturesSection.vue'
import Footer from '@/components/Footer.vue'

export default {
  components: {
    Header,
    Gallery,
    //   FeaturesSection,
    Footer
  }
}
</script>
./Index.vue