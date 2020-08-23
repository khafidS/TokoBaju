<template>
  <div class="home">
   <HeaderMastore />
   <HeroSection />
   <SliderProduct />
   <InstaMastore />
   <LogoMastore />
   <FooterMastore />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderMastore from '@/components/HeaderMastore.vue'
import HeroSection from '@/components/HeroSection.vue'
import SliderProduct from '@/components/SliderProduct.vue'
import InstaMastore from '@/components/InstaMastore.vue'
import LogoMastore from '@/components/LogoMastore.vue'
import FooterMastore from '@/components/FooterMastore.vue'


export default {
  name: 'Home',
  components: {
    HeaderMastore,
    HeroSection,
    SliderProduct,
    InstaMastore,
    LogoMastore,
    FooterMastore
  }
}
</script>
