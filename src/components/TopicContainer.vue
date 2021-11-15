<template>
  <div class="topic-container" :style="{backgroundColor: this.bgColor}">
    <slot></slot>
    <div class="back-to-top">
      <a href="#main-banner">↑ Back to Top ↑</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TopicContainer',
  props: {
    bgColor: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@media only screen and (min-width: 768px) {
  .topic-container {
    height: 100vh;
  }
  .back-to-top {
    position: fixed;
    bottom: 2%;
    right: 2%;
    font-size: small;
  }
}
</style>
