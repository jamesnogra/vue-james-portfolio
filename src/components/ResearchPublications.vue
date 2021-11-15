<template>
  <div id="research-publications" class="section-main-container">
    <div class="vertical-middle">
      <h1 class="centered">Research Publications</h1>
      <div class="two-divs-container">
        <div class="left-or-right-or-center">
          <div class="with-text-padding center-if-mobile add-left-padding">
            <a class="research-links" href="http://www.ijmlc.org/index.php?m=content&c=index&a=show&catid=106&id=1093">Baybáyin Character Recognition Using Convolutional Neural Network</a>
            <a class="research-links" href="https://ieeexplore.ieee.org/document/8821789">LSTM Neural Networks for Baybáyin Handwriting Recognition</a>
            <a class="research-links" href="http://www.warse.org/IJATCSE/static/pdf/file/ijatcse26913sl2020.pdf">Text Analysis on Instagram Comments to Better Target Users with Product Advertisements</a>
            <a class="research-links" href="https://www.ijterm.org/index.php/jset/article/download/69/57/114">Predictive Model for Autistic Spectrum Disorder with Neural Network Application</a>
            <a class="research-links" href="https://www.jardcs.org/abstract.php?id=5699">Face Mask Usage Detection Using Inception Network</a>
            <a class="research-links" href="http://www.warse.org/IJATCSE/static/pdf/file/ijatcse30913sl2020.pdf">Inception Network for Baybáyin Handwriting Recognition</a>
            <a class="research-links" href="http://www.warse.org/IJATCSE/static/pdf/file/ijatcse23913sl2020.pdf">Java Plum Leaf Classification Using a Mobile Application with Inception Network</a>
            <a class="research-links" href="https://ieeexplore.ieee.org/document/9072747">Calculating the Probability Outcomes of the Monty Hall Problem Using A Web-Based Simulation</a>
            <a class="research-links" href="https://www.jardcs.org/abstract.php?id=2819">Learn Baybáyin: An e-Learning Mobile Application Using a Convolutional Neural Network</a>
            <a class="research-links" href="https://www.ijterm.org/index.php/jset/article/view/37">Classifying Java plum (Eugenia jambolana) Leaf for Tobacco Cigarette Wrapper using Convolutional Neural Network</a>
          </div>
        </div>
        <div class="left-or-right-or-center">
          <div class="image-container"><img src="/images/research.jpg" /></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ResearchPublications'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.image-container {
  border-radius: 10px;
  overflow: hidden;
  width: 400px;
  height: 300px;
  margin-left: 100px;
}
.image-container img {
  flex: 1;
  height: 100%;
}
.research-links {
  display: block;
  margin-bottom: 15px;
}
@media only screen and (max-width: 768px) {
  .image-container {
    width: 100%;
    text-align: center;
    margin-left: 0px;
  }
  .image-container img {
    width: 90%;
    border-radius: 10px;
  }
}
@media only screen and (min-width: 768px) {
  .add-left-padding {
    padding-left: 15%;
  }
}
</style>
