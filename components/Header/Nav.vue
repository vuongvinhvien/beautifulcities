<template>
  <div class="nav">
    <ul class="nav-menu">
      <li class="nav-menu-item"><n-link :to="'/'">Home</n-link></li>
      <li class="nav-menu-item"><n-link :to="'/about'">About</n-link></li>
      <li class="nav-menu-item"><n-link :to="'/blog'">Blog</n-link></li>
      <li class="nav-menu-item"><n-link :to="'/gallery'">Gallery</n-link></li>
      <li class="nav-menu-item"><n-link :to="'/visit'">Visit</n-link></li>
      <li class="nav-menu-item"><n-link :to="'/contact'">Contact</n-link></li>
    </ul>
  </div>
</template>
<style lang="scss" scoped>
.nav {
  display: flex;
  flex-direction: columns;
  height: 80px;
  align-items: center;
  .nav-menu {
    display: flex;
    align-items: center;
    margin-left: 50px;
    margin-bottom: 0;
    min-height: 100%;
    .nav-menu-item {
      font-size: 18px;
      font-weight: 700;
      margin: 10px;
      a {
        color: #ccc;
      }
      a:hover {
        color: black;
      }
    }
  }
}
</style>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>
