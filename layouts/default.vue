<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
  import Header from '@/components/Header';
  import Footer from '@/components/Footer'
  export default {
    name: "Default",
    components: {
      Header,
      Footer
    }
  }
</script>
