<template>
<div id="quote-section">
    <div id="quote-sec-container">
        <Quote />
        <div class="about-news-wrap">
            <BriefAbout />
            <Newsletter />
        </div>  
    </div>
</div>    
</template>

<script>
import BriefAbout from './BriefAbout.vue';
import Newsletter from './Newsletter.vue';
import Quote from './Quote.vue';

export default {
    components: {
        BriefAbout,
        Newsletter,
        Quote
    }
}
</script>

<style lang="scss">
#quote-section{
    width: 100%;
    min-height: 100vh;
    background: $blue-light;
    display: flex;
    align-items: center;
    justify-content: center;
    #quote-sec-container{
        width: 70%;
        margin: 0 auto;
        .about-news-wrap{
            width: 100%;
            display: flex;
            justify-content: space-between;
        }
    }
}
</style>