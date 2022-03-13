<template>
  <div class="container">
    <div>
      <img src="@/assets/images/contents/1.jpg" class="max-w-full" />
    </div>
    <div class="wrapper row">
      <div class="column transform transition duration-500 hover:scale-110">
        <nuxt-link to="mulProject">
          <img src="@/assets/images/contents/3.jpg" class="max-w-full" />
        </nuxt-link>
      </div>
      <div class="column">
        <div class="item2 transform transition duration-500 hover:scale-110">
          <nuxt-link to="shoesBags">
            <img
              src="@/assets/images/contents/21.jpg"
              class="max-w-full"
              width="330"
              height="400"
            />
          </nuxt-link>
        </div>
        <div class="item3 transform transition duration-500 hover:scale-110">
          <nuxt-link to="schoolProjects">
            <img
              src="@/assets/images/contents/27.jpg"
              class="max-w-full h-64"
              width="330"
            />
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import 'tw-elements'

export default {}
</script>

<style scoped>
* {
  box-sizing: border-box;
}

.container {
  scroll-behavior: smooth;
  margin: -80px 0px 50px 0px;
}

.wrapper {
  margin: 0px 0px 0px 200px;
}

.row {
  display: flex;
  flex-wrap: wrap;
}

.column {
  flex: 50%;
  padding: 0 10px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
}

.item2 {
  margin: 0px 30px 0px 40px;
}

.item3 {
  margin: 30px 30px 70px 40px;
}
</style>