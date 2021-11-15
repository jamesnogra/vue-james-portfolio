<template>
  <div id="baybayin-handwriting-recognition" class="section-main-container">
    <div class="vertical-middle">
      <h1 class="centered">Baybáyin Handwriting Recognition Using Convolutional Neural Network</h1>
      <div class="two-divs-container">
        <div class="left-or-right-or-center">
          <div class="with-text-padding center-if-mobile add-left-padding">
            <p>Based from the research paper <a href="http://www.ijmlc.org/index.php?m=content&c=index&a=show&catid=106&id=1093">Baybáyin Character Recognition Using Convolutional Neural Network</a>.</p>
            <p>The Philippine Congress approved the House Bill 1022 which states that the Baybáyin will be used as the national writing system of the country. The Department of Education and National Commission for Culture and Arts has vowed to reintroduce this old writing system back to the country.</p>
            <p>To speed up the learning process, a Convolutional Neural Network (CNN) was designed and created for the classification of hand-drawn characters. The model achieved a 94% accuracy rate using a validation data. </p>
          </div>
        </div>
        <div class="left-or-right-or-center">
          <div class="image-container"><img src="/images/cnn.png" /></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BaybayinHandwritingRecognition'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.image-container {
  border-radius: 10px;
  overflow: hidden;
  width: 224px;
  height: 424px;
  margin-left: 100px;
}
.image-container img {
  flex: 1;
  height: 100%;
}
@media only screen and (max-width: 768px) {
  .image-container {
    width: 100%;
    text-align: center;
    margin-left: 0px;
  }
}
@media only screen and (min-width: 768px) {
  .add-left-padding {
    padding-left: 25%;
  }
}
</style>
