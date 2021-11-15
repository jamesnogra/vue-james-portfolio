<template>
  <div id="about" class="section-main-container">
    <div class="vertical-middle">
      <h1 class="centered">James Arnold E. Nogra</h1>
      <div class="two-divs-container">
        <div class="left-or-right-or-center">
          <div class="main-image-container">
            <div alt="James Arnold Nogra" class="image-container"  :key="'photo-img-'+index" v-for="(photo, index) in aboutPhotos">
              <img :src="photo" />
            </div>
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
  name: 'About',
  data() {
    return {
      aboutPhotos: [
          '/images/img1.jpg',
          '/images/img2.jpg',
          '/images/img3.jpg',
          '/images/img4.jpg',
          '/images/img5.jpg',
          '/images/img6.jpg',
          '/images/img7.jpg',
          '/images/img8.jpg',
          '/images/img9.jpg',
      ]
    }
  }
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
