<template>
  <div class="home-container">
    <div class="home-container1">
      <div class="home-container2">
        <DangerousHTML
          html="<iframe
    width='866'
    height='487'
    src='https://www.youtube.com/embed/xBTq5ngwIJA'
    title='How to host a website for free using TeleportHQ'
    frameborder='0'
    allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share'
    referrerpolicy='strict-origin-when-cross-origin'
    allowfullscreen
  ></iframe>
  "
        ></DangerousHTML>
      </div>
    </div>
    <content-list6></content-list6>
    <app-features15></app-features15>
    <lottie-vue-player
      :src="`https://lottie.host/c404786e-2d84-4239-a092-5fa55366d5a7/DRPRrsgJH4.json`"
      :speed="1"
      :autoplay="true"
      :backgroundColor="transparent"
      class="home-lottie-node"
    ></lottie-vue-player>
    <div class="home-container3">
      <div class="home-container4">
        <DangerousHTML
          html="<iframe
    width='866'
    height='487'
    src='https://www.youtube.com/embed/xBTq5ngwIJA'
    title='How to host a website for free using TeleportHQ'
    frameborder='0'
    allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share'
    referrerpolicy='strict-origin-when-cross-origin'
    allowfullscreen
  ></iframe>
  "
        ></DangerousHTML>
      </div>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/dist/vue/lib.js'

import ContentList6 from '../components/content-list6'
import AppFeatures15 from '../components/features15'

export default {
  name: 'Home',
  props: {},
  components: {
    DangerousHTML,
    ContentList6,
    AppFeatures15,
  },
  head: {
    title: 'Sniveling Practical Flamingo',
    meta: [
      {
        property: 'og:title',
        content: 'Sniveling Practical Flamingo',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-container1 {
  width: 868px;
  height: 487px;
}
.home-container2 {
  display: contents;
}
.home-lottie-node {
  width: 300px;
  height: 300px;
}
.home-container3 {
  width: 868px;
  height: 487px;
}
.home-container4 {
  display: contents;
}
</style>
