<template>
  <NavBar/>
  <div class="container">
    <div class="slogan-div">
      <p class="slogan">
        Mudando o mundo,<br />
        um plástico <br />por vez.
      </p>
    </div>
    <div class="image-div">
      <img class="loop rotating" src="../assets/recycloop.png" />
    </div>
  </div>
</template>

<script>
import NavBar from './NavBar.vue';

export default {
  name: "BannerBar",
  components: {
    NavBar,
  }
};

</script>

<style>
.container {
  display: flex;
  width: 100%;
  background-image: url('../assets/plastica.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  padding-bottom: 40px;
}
.slogan {
  text-align: left;
  font-size: 55px;
  font-family: "arboria-bold";
  color: green;
}
.image-div {
  flex: 1;
  display: flex;
  justify-content: right;
}
.slogan-div {
  margin: 90px;
  padding-left: 90px;
  flex: 1;
}
.loop {
  transform: rotate(90deg);
  justify-self: right;
  margin-right: 70px;
}
.rotating {
   animation: rotate 40s infinite;
}

@keyframes rotate {
   from { transform: rotate(0deg); }
   to { transform: rotate(360deg); }
}
@media screen and (max-width: 992px) {
  .container {
    flex-direction: column;
  }
  .slogan {
    font-size: 40px;
  }

  .slogan-div {
    flex: 2;
    margin: 0px;
    padding-right: 10px;
  }

  .image-div {
    position: absolute;
    right: 0;
    top: 0;
    overflow: hidden;
  }

  .left {
    flex-direction: column-reverse;
  }

  .loop {
    height: 200px;
    margin-right: -100px;
    filter: blur(2px);
  }
}
</style>