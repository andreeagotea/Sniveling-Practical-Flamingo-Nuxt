<template>
  <div class="app-component-container"><content-list4></content-list4></div>
</template>

<script>
import ContentList4 from './content-list4'

export default {
  name: 'AppComponent',
  props: {},
  components: {
    ContentList4,
  },
}
</script>

<style scoped>
.app-component-container {
  width: 100%;
  height: 400px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
</style>
