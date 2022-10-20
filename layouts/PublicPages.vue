<template>
  <div class="d-flex flex-column">
    <HeaderComponent />
    <Nuxt />
    <FooterPage />
  </div>
</template>

<script>
import HeaderComponent from '~/components/Header'
import FooterPage from '~/components/Footer'
export default {
  name: 'PublicPages',
  components: {
    FooterPage,
    HeaderComponent
  }
}
</script>

<style scoped>

</style>
