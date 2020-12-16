<template>
  <div>
    <VueSlickCarousel :arrows="true" :dots="true">
      <div><Hero /></div>
      <img src="../assets/image/banner2.png" alt="" />
      <img src="../assets/image/banner3.png" alt="" />
      <img src="../assets/image/banner4.png" alt="" />
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: 'MyComponent',
  components: { VueSlickCarousel },
}
</script>
