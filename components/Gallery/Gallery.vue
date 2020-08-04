<template>
  <section class="gallery">
    <div class="gallery__group">
      <div class="gallery__group-item">
        <img class="image" src="../../assets/images/2.jpg" />
        <h4>City example 1</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas
          laboriosam nesciunt...
        </p>
      </div>
      <div class="gallery__group-item">
        <img class="image" src="../../assets/images/3.jpg" />
        <h4>City example 2</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas
          laboriosam nesciunt...
        </p>
      </div>
      <div class="gallery__group-item">
        <img class="image" src="../../assets/images/4.jpg" />
        <h4>City example 3</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas
          laboriosam nesciunt...
        </p>
      </div>
      <div class="gallery__group-item">
        <img class="image" src="../../assets/images/2.jpg" />
        <h4>City example 1</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas
          laboriosam nesciunt...
        </p>
      </div>
      <div class="gallery__group-item">
        <img class="image" src="../../assets/images/3.jpg" />
        <h4>City example 2</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas
          laboriosam nesciunt...
        </p>
      </div>
      <div class="gallery__group-item">
        <img class="image" src="../../assets/images/4.jpg" />
        <h4>City example 3</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas
          laboriosam nesciunt...
        </p>
      </div>
    </div>
  </section>
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>
<style lang="scss" scoped>
.gallery {
  background-color: rgb(146, 216, 140);
  display: flex;
  flex-direction: columns;
  width: inherit;
  &__group {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    max-width: inherit;
    flex-wrap: wrap;
    &-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 20px;
      width: 33.3%;
      img {
        width: 100%;
        object-fit: cover;
      }
    }
  }
}
</style>
