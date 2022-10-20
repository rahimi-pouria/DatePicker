<template>
  <div class="d-flex">
    <ContentComponent />
  </div>
</template>

<script>
import ContentComponent from '~/components/Home/Content'
export default {
  name: 'IndexPage',
  components: { ContentComponent },
  layout: 'PublicPages'
}
</script>

<style></style>
