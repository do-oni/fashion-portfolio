<template>
  <div class="text-center bg-gray-50 text-gray-800 py-20 px-6">
    <div class="title">
      <h1 class="text-5xl font-bold mt-0 mb-6">Haeyeon Seo</h1>
    </div>
    <div class="content">
      <section id="email">
        <a href="mailto:haeyeon5119@gmail.com">
          <fa-layers full-width class="fa-2x">
            <fa :icon="faEnvelope" />
          </fa-layers>
          <span>haeyeon5119@gmail.com</span>
        </a>
      </section>
      <section id="insta">
        <a href="https://www.instagram.com/51_19">
          <fa-layers full-width class="fa-2x">
            <fa :icon="faInstagram" />
          </fa-layers>
          <span>51_19</span>
        </a>
      </section>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { fas } from '@fortawesome/free-solid-svg-icons'
import { faEnvelope } from '@fortawesome/free-regular-svg-icons'
import { faInstagram } from '@fortawesome/free-brands-svg-icons'

export default Vue.extend({
  computed: {
    fas() {
      return fas
    },
    faEnvelope() {
      return faEnvelope
    },
    faInstagram() {
      return faInstagram
    },
  },
})
</script>

<style scoped>
.title {
  margin: 100px;
}

.content {
  margin: -50px;
}

#email {
  margin-bottom: 30px;
}

#insta {
  margin-bottom: 30px;
}
</style>