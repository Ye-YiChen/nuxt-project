<template>
  <div>
    <!-- 头部 -->
    <Header />
    <!-- 主体 -->
    <Nuxt />
    <!-- 底部 -->
    <Footer />
  </div>
</template>

<script>
import Footer from '../components/layout/Footer.vue'
import Header from '../components/layout/Header.vue'
import Tutorial from '../components/Tutorial.vue'
export default {
  components: { Header, Footer, Tutorial },
}
</script>

<style>
</style>