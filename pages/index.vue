<template>
    <div>
      <!-- <Navbar />
      <HeroSection />
      <FeaturesSection /> -->
      <Header />
      <Footer />
    </div>
  </template>
  
  <script>
  import Header from '@/components/Header.vue'
//   import HeroSection from '@/components/HeroSection.vue'
//   import FeaturesSection from '@/components/FeaturesSection.vue'
  import Footer from '@/components/Footer.vue'
  
  export default {
    components: {
        Header,
    //   HeroSection,
    //   FeaturesSection,
      Footer
    }
  }
  </script>
  ./Index.vue