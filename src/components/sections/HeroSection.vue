<template>
  <main>
 <section class="hero-section text-center d-flex justify-content-center align-items-center">
  <div class="container heroContent">
    <h1>Hillsong Church</h1>
    <p>Welcome Home</p>
  </div> 
 </section>

 <section>
  <div class="container text-center py-5">
    <h2>Hillsong is a church that believes in Jesus, a church that loves God and people.</h2>
    <p>Overwhelmed by the gift of salvation we have found in Jesus, we have a heart for authentic worship, are passionate about the local church, and are on mission to see God’s kingdom established across the earth.</p>
  </div>
 </section>

 <section class="musicSection">
  <div class="container">
    <h2>Music</h2>
<p>The sound of our Worship</p>

<div class="container">
  <img src="" alt="">
  <h3 id="musicTitle"></h3>
  <p id="musicContent"></p>
</div>
  </div>

 </section>

 <section class="hillsongOnline py-5 text-center d-flex align-items-center justify-content-center text-center">
<div class="container">
  <h2>Hillsong Online</h2>
  <p class="w-75 mx-auto">Hillsong Online exists to empower our church for mission in a digital age. We believe the Holy Spirit will be tangible and present in every heart and home as we gather together from all over the world.</p>
  <router-link to="">Learn More</router-link>
</div>
 </section>

 <section class="text-center py-5 unityAndBelonging">
  <div class="container">
    <h2>Unity and Belonging</h2>
    <p class="w-75 mx-auto">Hillsong Church is a multi-generational church made up of people from richly diverse cultural and ethnic backgrounds—committed to unity and belonging centered on Christ. We are intentional about building a church where people of all ages and backgrounds participate fully in the body of Christ—in line with how Jesus prayed (Jn 17:22-23), with what the early church modeled (Acts 2, Gal 3:28) and with what heaven will be like (Rev 7:9). This commitment is part of our vision to be a healthy church changing lives through Christ. As part of our Welcome Home Value, we are invitational—creating warm environments where every one is valued.</p>
  </div>
 </section>

 <section class="blogBanner text-center d-flex justify-content-center align-items-center">
  <div class="container w-50">
    <h2>Hillsong Collected</h2>
    <h3>Our Blog</h3>
    <p class="w-75 mx-auto">Stories, thoughts and articles about what
Jesus is doing in our world, and how we outwork that
through our local churches.</p>
<router-link to="">START READING</router-link>
  </div>
 </section>

 <section class="hillsongCollege text-center d-flex align-items-center">
<div class="container w-75">
  <h2>Hillsong College</h2>
  <p>Find your community. Prepare for purpose.</p>
  <p class="w-75 mx-auto">Strategically placed within the life of our local church in Sydney, Hillsong College allows you to apply the skills you will learn in a practical ministry setting so that you can lead and impact in your world.</p>
  <router-link>HILLSONG COLLEGE</router-link>
</div>
 </section>
 </main>
</template>

<script setup>
// import BaseBtn from '../common/BaseBtn.vue';
// import homeHero from 'src/Assets/image';
// import musicCard from '/public/music1.json';

</script>

<style scoped>
.hero-section{
  background: url('/src/Assets/image/homeHeroSection.gif');
  height: 70vh;
  background-repeat: no-repeat;
  background-size: cover;
}
.heroContent{
  color:white;
}
.hillsongOnline{
  background:#d7d7d7;
  height: 70vh;
}

/* Blog Banner Section */
.blogBanner{
  background: url(/src/Assets/image/blogBanner.jpg);
  height: 70vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  color:white;
}
.hillsongCollege{
  background: url(/src/Assets/image/hillsongCollege.png);
  height: 70vh;
  color:white;
}
</style>
