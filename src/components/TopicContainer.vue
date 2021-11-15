<template>
  <div class="topic-container" :style="{backgroundColor: this.bgColor}">
    <slot></slot>
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
}
</style>
