<template>
  <footer class="">
    <div>
      <p>
        &copy; copy right
        <a href="http://facebook.com/vuongvinhvien"> contact me</a>
      </p>
    </div>
  </footer>
</template>
<style lang="scss" scoped>
footer {
  height: 80px;
  background-color: rgba(119, 102, 102, 0.521);
  div {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    width: inherit;
    height: inherit;
    p {
      font-size: 18px;
      font-weight: 700;
    }
  }
}
</style>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>
