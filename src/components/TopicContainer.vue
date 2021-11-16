<template>
  <div class="topic-container" :style="{backgroundColor: this.bgColor}">
    <slot></slot>
    <div class="back-to-top">
      <a class="fixed-links" href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fjames.iamcebu.com%2F&t=James Arnold E. Nogra Portfolio"
         onclick="javascript:window.open(this.href, '', 'menubar=no,toolbar=no,resizable=yes,scrollbars=yes,height=300,width=600');return false;"
         target="_blank" title="Share on Facebook">
        Share to Facebook ⓕ
      </a>
      <a class="fixed-links" href="https://twitter.com/share?hashtags=awesome,sharing,portfolio&text=View the portfolio website of James Arnold Nogra&via=fallguyjames">
        Share to Twitter ⓣ
      </a>
      <a class="fixed-links" href="#main-banner">Back to Top ↑</a>
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
.fixed-links {
  margin-right: 10px;
}
@media only screen and (max-width: 768px) {
  .back-to-top {
    text-align: center;
    font-size: x-small;
    position: fixed;
    bottom: 0px;
    width: 100%;
    background-color: #f7f2c3;
    padding: 5px;
  }
}
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
