<template>
  <div id="homepage">
    <Hero />

    <!-- Popular Post -->
    <PopularPost />

    <!-- Recent post and instagram feed section -->
    <div class="recent-post-instagram container">
      <!-- Recent Post -->
      <RecentPost />
      <!-- Instagram Feed -->
      <InstagramSection />
    </div>
    
    <!-- Section for quote, brief about and newsletter -->
    <QuoteSection />
  </div>
</template>

<script>
import Navigation from '../components/Header/Navigation.vue';
import Hero from '../components/Header/Hero.vue';
import PopularPost from '../components/Homepage/PopularPost.vue';
import RecentPost from '../components/Homepage/RecentPost.vue';
import InstagramSection from '../components/Homepage/InstagramSection.vue'
import QuoteSection from '../components/Homepage/QuoteSection.vue';
import Footer from '../components/Footer/Footer.vue';


export default {
  components: {
    Navigation,
    Hero,
    PopularPost,
    RecentPost,
    QuoteSection,
    Footer
  }
}
</script>


<style>
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
} */
.post-title{
  font-size: 18px;
  line-height: 29px;
  margin-top: .5em;
}
.recent-post-instagram{
  padding: 7em 0;
  display: flex;
  justify-content: space-between;
}
</style>
