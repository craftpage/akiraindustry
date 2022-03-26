<template>
  <Top msg="輝工業" />
  <News msg="輝工業" />
  <Vision msg="幸せの創造" />
  <Product />
  <About msg="輝工業" />
  
</template>

<script>
import Top from './components/Top.vue'
import News from './components/News.vue'
import Vision from './components/Vision.vue'
import Product from './components/Product.vue'
import Service from './components/Service.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
    Top,
    News,
    Vision,
    Product,
    Service,
    About
  }
}
</script>
