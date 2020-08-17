<template>
  <div>
    
    <Navigation />
    
    <main>
      <Nuxt />
    </main>

    <Footer />
    
  </div>
</template>

<script>
import Navigation from '../components/Header/Navigation.vue';
import Footer from '../components/Footer/Footer.vue';

export default {
  components: {
    Navigation,
    Footer
  }
}
</script>

<style lang="scss">
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
h1,
h2,
h3,
h4,
h5,
h6{
  font-family: $poppins;
}
p{
  font-family: $lora;
}
.container{
  width: 88%;
  margin: 0 auto;
}
</style>
