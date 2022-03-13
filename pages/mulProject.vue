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
  name: 'mulProject',
  data() {
    return {
      images: [] = [
        {
          url: require("@/assets/images/contents/3-1.jpg")
        },
        {
          url: require("@/assets/images/contents/4.jpg")
        },
        {
          url: require("@/assets/images/contents/5.jpg")
        },
        {
          url: require("@/assets/images/contents/6.jpg")
        },
        {
          url: require("@/assets/images/contents/7.jpg")
        },
        {
          url: require("@/assets/images/contents/8.jpg")
        },
        {
          url: require("@/assets/images/contents/9.jpg")
        },
        {
          url: require("@/assets/images/contents/10.jpg")
        },
        {
          url: require("@/assets/images/contents/11.jpg")
        },
        {
          url: require("@/assets/images/contents/12.jpg")
        },
        {
          url: require("@/assets/images/contents/13.jpg")
        },
        {
          url: require("@/assets/images/contents/14.jpg")
        },
        {
          url: require("@/assets/images/contents/15.jpg")
        },
        {
          url: require("@/assets/images/contents/16.jpg")
        },
        {
          url: require("@/assets/images/contents/17.jpg")
        },
        {
          url: require("@/assets/images/contents/18.jpg")
        },
        {
          url: require("@/assets/images/contents/19.jpg")
        },
        {
          url: require("@/assets/images/contents/20.jpg")
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