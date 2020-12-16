<template>
  <div>
    <VueSlickCarousel :arrows="true" :dots="true">
      <div><Hero /></div>
      <div><Hero /></div>
      <div><Hero /></div>
      <div><Hero /></div>
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
