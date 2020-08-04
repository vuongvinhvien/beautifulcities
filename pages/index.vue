<template>
  <div class="container">
    <Logo></Logo>
    <Nav></Nav>
    <Image-Header></Image-Header>

  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from '@/components/Header/Logo.vue'
import Nav from '@/components/Header/Nav.vue'
import ImageHeader from '@/components/Header/ImageHeader.vue'

export default Vue.extend({
  components: {
    Logo,
    Nav,
    ImageHeader,
  },
})
</script>

<style>
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
