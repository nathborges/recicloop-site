<template>
  <BannerBar/>
  <AboutBar />
  <QuestionBar />
  <BagBar />
</template>

<script>
import BannerBar from './components/BannerBar.vue'; 
import AboutBar from './components/AboutBar.vue'; 
import QuestionBar from './components/QuestionBar.vue';
import BagBar from './components/BagBar.vue';

export default {
  name: 'App',
  components: {
    BannerBar,
    AboutBar,
    QuestionBar,
    BagBar
}
}
</script>

<style>
 @import "@/assets/css/global.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
body {
  margin: 0;
 }
</style>
