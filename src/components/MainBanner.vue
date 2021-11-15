<template>
  <div class="links-container">
    <a class="link-items" href="#about">About</a>
    <a class="link-items" href="#face-mask-detection">Face Mask Detection</a>
    <a class="link-items" href="#taglish-sentiment-analyzer">Taglish Sentiment Analyzer</a>
    <a class="link-items" href="#baybayin-handwriting-recognition">Baybayin Handwriting Recognition</a>
    <a class="link-items" href="#web-development">Web Development</a>
    <a class="link-items" href="#research-publications">Research Publications</a>
  </div>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.links-container {
  background-color: #f7f2c3;
  display: flex;
  overflow-x: auto;
}
.link-items {
  margin: 15px 5px 15px 5px;
  padding: 5px;
  text-decoration: none;
  transition: 0.5s;
  opacity: 0.6;
  color: #474747;
  white-space: nowrap;
}
.link-items:hover {
  opacity: 1;
  color: #3b3b3b;
}
</style>
