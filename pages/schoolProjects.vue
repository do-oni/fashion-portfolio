<template>
  <div class="container">
    <div v-for="image in images" :key="image.id">
      <img :src="image.url" />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'schoolProjects',
  data() {
    return {
      images: [] = [
        {
          url: require("@/assets/images/contents/27-1.jpg")
        },
        {
          url: require("@/assets/images/contents/28.jpg")
        },
        {
          url: require("@/assets/images/contents/29.jpg")
        },
        {
          url: require("@/assets/images/contents/30.jpg")
        },
        {
          url: require("@/assets/images/contents/31.jpg")
        },
        {
          url: require("@/assets/images/contents/32.jpg")
        },
      ]
    }
  }
})
</script>

<style scoped>
.container {
  width: 1050px;
  height: 800px;
  margin: 175px;
  position: relative;
  scroll-behavior: smooth;
}

img {
  margin: -70px 0px 50px 0px;
  padding-bottom: 50px;
}
</style>