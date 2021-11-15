<template>
  <div id="face-mask-detection" class="section-main-container">
    <div class="vertical-middle">
      <h1 class="centered">Face Mask Usage Detection Using Inception Network</h1>
      <div class="two-divs-container">
        <div class="left-or-right-or-center">
          <div class="with-text-padding center-if-mobile add-left-padding">
            <p>Derived from the research paper <a href="https://www.jardcs.org/abstract.php?id=5699">Face Mask Usage Detection Using Inception Network</a>. The full article <a href="https://techblog.fullspeedtechnologies.com/post/face-mask-usage-detection">Detecting Face Mask Usage Using Inception Network</a> explains the installation and usage of the neural network.</p>
            <p>With the ongoing pandemic, one of the tools that we have that has proven to be effective in preventing the spread of the COVID-19 virus is through wearing a face mask. However, there are some people who are not wearing it properly.</p>
            <p>This Inception Network has a 98% accuracy rate in detecting face mask usage in faces. The neural network was trained using thousands of face images.</p>
          </div>
        </div>
        <div class="left-or-right-or-center">
          <div class="image-container"><img src="/images/demo-face-mask.gif" /></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FaceMaskUsage'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.image-container {
  width: 400px;
  height: 224px;
  border-radius: 10px;
  overflow: hidden;
}
@media only screen and (max-width: 768px) {
  .image-container {
    width: 100%;
    text-align: center;
  }
  .image-container img {
    width: 90%;
    border-radius: 10px;
  }
}
@media only screen and (min-width: 768px) {
  .add-left-padding {
    padding-left: 25%;
  }
}
</style>
