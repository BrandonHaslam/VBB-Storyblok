<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>
 
<script>
export default {
  components: {
    Header: () => import('~/components/layout/TheHeader.vue'),
    Footer: () => import('~/components/layout/TheFooter.vue'),
  },
}
</script>