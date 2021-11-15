<template>
  <div id="about" class="section-main-container">
    <div class="vertical-middle">
      <h1 class="centered">James Arnold E. Nogra</h1>
      <div class="two-divs-container">
        <div class="left-or-right-or-center">
          <div class="main-image-container">
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/img1.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/img2.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/img3.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/img4.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/img5.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/img6.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/img7.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/img8.png" /></div>
            <div alt="James Arnold Nogra" class="image-container"><img src="/images/img9.png" /></div>
          </div>
        </div>
        <div class="left-or-right-or-center">
          <div class="with-text-padding center-if-mobile">
            <div class="about-items"><b>LinkedIn:</b> <a href="https://ph.linkedin.com/in/thejamesarnold">@thejamesarnold</a></div>
            <div class="about-items"><b>Instagram:</b> <a href="https://www.instagram.com/thejamesarnold/">@thejamesarnold</a></div>
            <div class="about-items"><b>Blog:</b> <a href="https://www.iamcebu.com/">The Rookie Blogger</a></div>
            <div class="about-items"><b>Skills:</b> PHP, JavaScript, MySQL, NodeJS, MongoDB, Python, Tensorflow, React Native, and VueJS</div>
            <div class="about-items"><b>Hobbies:</b> Mountain Bike, Computer Games</div>
            <div class="about-items"><b>Games Played:</b> Fall Guys, Ragnarok M, Ragnarok Classic, Stronghold Crusader, Pokemon Go, Pangya</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About'
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
}
.about-items {
  margin-bottom: 5px;
}
</style>
