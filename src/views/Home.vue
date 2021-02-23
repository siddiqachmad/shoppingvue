<template>
  <div class="home">
    <HeaderShayna/>
    <Slider/>
    <ItemBarang/>
    <ItemGallery/>
    <ItemPartner/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import Slider from '@/components/SliderComponent.vue'
import ItemBarang from '@/components/ItemBarang.vue'
import ItemGallery from '@/components/ItemGallery.vue'
import ItemPartner from '@/components/ItemPartner.vue'
import Footer from '@/components/Footer.vue'
export default {
  name: 'Home',
  components: {
    HeaderShayna,
    Slider,
    ItemBarang,
    ItemGallery,
    ItemPartner,
    Footer
  }
}
</script>
