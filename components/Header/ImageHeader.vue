<template>
  <div class="image-header">
    <h2>Visit Beautiful Cities</h2>
    <p>
      The project has a standard configuration of Asp.Net Core Web Api (2.2
      version) and also a Vue JS project setup on the ClientApp folder, with all
      the basic and needed configurations. All the extra needed settings on
      Asp.Net Core Startup file were already made as well, including the
      mandatory packages for Vue JS SPA Middleware:
    </p>
  </div>
</template>

<style lang="scss">
.image-header {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.7)),
    url(../../assets/images/1.jpg);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: #fff;
  height: 500px;
  h2 {
    color: #fff;
    text-transform: uppercase;
    font-size: 35px;
    font-weight: 300;
  }
  p {
    text-align: center;
    margin: 10px 100px;
  }
}
</style>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>
