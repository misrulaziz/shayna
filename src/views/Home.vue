<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <HeaderShayna/>
    <HeroShayna/>
    <BannerShayna/>
    <InstaShayna/>
    <PartnerShayna/>
    <FooterShayna/>

  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import BannerShayna from '@/components/BannerShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import PartnerShayna from '@/components/PartnerShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    HeaderShayna,
    HeroShayna,
    BannerShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
