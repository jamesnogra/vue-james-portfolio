<template>
  <div id="app">
    <MainBanner />
    <TopicContainer bgColor="#fffcde">
      <About />
    </TopicContainer>
    <TopicContainer bgColor="#fbffcc">
      <FaceMaskUsage />
    </TopicContainer>
    <TopicContainer bgColor="#fffcde">
      <TaglishSentimentAnalyzer />
    </TopicContainer>
  </div>
</template>

<script>
import MainBanner from './components/MainBanner.vue'
import TopicContainer from './components/TopicContainer.vue'
import About from './components/About.vue'
import FaceMaskUsage from './components/FaceMaskUsage.vue'
import TaglishSentimentAnalyzer from './components/TaglishSentimentAnalyzer.vue'

export default {
  name: 'App',
  components: {
    MainBanner,
    TopicContainer,
    About,
    FaceMaskUsage,
    TaglishSentimentAnalyzer,
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Yuji+Syuku&display=swap');
#app {
  font-family: 'Yuji Syuku', serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
a {
  color: #474747;
  text-decoration-thickness: 4px;
  text-decoration-color: #d7f542;
}
html, body {
  margin: 0px;
}
.spacer {
  width: 100%;
  height: 1px;
}
.centered {
  text-align: center;
}
.section-main-container {
  display: table;
  width: 100%;
  height: 90%;
}
.vertical-middle {
  display: table-cell;
  vertical-align: middle;
}
.left-or-right-or-center {
  width: 50%;
  float: left;
}
/* exclusive for mobile phones: */
@media only screen and (max-width: 768px) {
  .left-or-right-or-center {
    width: 100%;
  }
  .center-if-mobile {
    text-align: center;
  }
  .center-if-mobile b {
    display: block;
  }
}
/* exclusive for desktop: */
@media only screen and (min-width: 768px) {
  .two-divs-container {
    display: flex;
    align-items: center;
  }
}
.with-text-padding {
  padding: 25px;
}
</style>
