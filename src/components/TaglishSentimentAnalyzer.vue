<template>
  <div id="taglish-sentiment-analyzer" class="section-main-container">
    <div class="vertical-middle">
      <h1 class="centered">Taglish (Tagalog-English) Sentiment Analyzer</h1>
      <div class="two-divs-container">
        <div class="left-or-right-or-center right-align">
          <div class="image-container"><img :src="'/images/sen'+this.imageIndex+'.png'" /></div>
        </div>
        <div class="left-or-right-or-center">
          <div class="with-text-padding center-if-mobile add-right-padding">
            <p>Detects a Taglish (Tagalog-English) phrase whether it is positive or a negative statement. Using Embeddings, the model can rate from 0 (negative) to 100 (positive) a statement. The model was trained using thousands of tagged statements.</p>
            <p>You can try the Taglish Sentiment Analyzer at <a href="http://sentiment.iamcebu.com:8081/">http://sentiment.iamcebu.com:8081/</a>.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TaglishSentimentAnalyzer',
  data() {
    return {
      secondsToShowPerImage: 5,
      imageIndex: 1
    }
  },
  methods: {
    changeSentimentImage() {
      if (this.imageIndex < 8) {
        this.imageIndex++
      } else {
        this.imageIndex = 1
      }
    }
  },
  created() {
    this.interval = setInterval(() => this.changeSentimentImage(), this.secondsToShowPerImage*1000)
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.right-align {
  display: flex;
  justify-content: right;
}
.image-container {
  width: 75%;
  border-radius: 10px;
  overflow: hidden;
  text-align: right;
}
.image-container img {
  width: 100%;
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
  .add-right-padding {
    padding-right: 25%;
  }
}
</style>
