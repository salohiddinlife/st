<template>
<main class="main">
    <MainSlider/>
    <MainSaleProducts/>
    <MainArrivals/>
</main>
</template>

<script>
import MainSlider from '@/components/MainSlider.vue'
import MainSaleProducts from '@/components/MainSaleProducts.vue'
import MainArrivals from '@/components/MainArrivals.vue'

export default {
  components:{
    MainSlider,
    MainSaleProducts,
    MainArrivals
  },
  setup () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>