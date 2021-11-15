<template>
  <div id="web-development" class="section-main-container">
    <div class="vertical-middle">
      <h1 class="centered">Web Development</h1>
      <div class="two-divs-container">
        <div class="left-or-right-or-center">
          <div class="main-image-container">
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/logo-php.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/logo-node-js.jpg" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/logo-mysql.jpeg" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/logo-html5.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/logo-python.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/logo-tensorflow.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/logo-vue.png" /></div>
          </div>
        </div>
        <div class="left-or-right-or-center">
          <div class="with-text-padding center-if-mobile">
            PHP, JavaScript, MySQL, NodeJS, MongoDB, Python, Tensorflow, HTML5, and VueJS
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'WebDevelopment'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-image-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.image-container {
  width: 100px;
  height: 100px;
  border-radius: 100px;
  background-color: gray;
  margin: 10px;
  overflow: hidden;
}
.image-container img {
  flex: 1;
  height: 100%;
  width: 100%;
}
.about-items {
  margin-bottom: 5px;
}
</style>
