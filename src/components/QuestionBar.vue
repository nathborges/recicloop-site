<template>
  <div class="container-question-bar">
    <div>
      <h2>Como é reciclar no Recicloop?</h2>
    </div>
    <div class="flex-div">
      <div class="flex-div-image-wrapper">
        <img class="icon" src="../assets/trash.png" />
      </div>
      <div class="flex-div-text-wrapper">
        <p>Separe o lixo que será reciclado.</p>
      </div>
    </div>
    <div class="flex-div left">
      <div class="flex-div-text-wrapper">
        <p>
          Abra o aplicativo e busque o estabelecimento
          cadastrado mais próximo de sua casa.
        </p>
      </div>
      <div class="flex-div-image-wrapper">
        <img class="icon" src="../assets/cel.png" />
      </div>
    </div>
    <div class="flex-div right">
      <div class="flex-div-image-wrapper">
        <img class="icon" src="../assets/business.png" />
      </div>
      <div class="flex-div-text-wrapper">
        <p>
          Vá até o estabelecimento escolhido e ganhe pontos
          por volume de lixo reciclável entregue.
        </p>
      </div>
    </div>
    <div class="flex-div left">
      <div class="flex-div-text-wrapper">
        <p>
          Continue reciclando e coletando pontos, poderá trocá-los por recompensas no
          app.
        </p>
      </div>
      <div class="flex-div-image-wrapper">
          <img class="icon" src="../assets/rewards.png" />
        </div>
    </div>
  </div>
</template>
  
  <script>
export default {
  name: "QuestionBar",
};
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container-question-bar {
  background-color: #eef2ed;
  margin: 0;
  padding: 40px;
  display: flex;
  flex-direction: column;
}

.container-question-bar h2 {
  font-family: "arboria-bold";
  font-size: 40px;
  color: grey;
  margin: 0;
}

.container-question-bar p {
  font-family: "arboria1";
  font-size: 30px;
  color: grey;
}

.flex-div {
  display: flex;
  margin: 24px;
}

.flex-div-text-wrapper {
  flex: 0.5;
  justify-self: left;
  align-self: center;
  align-items: center;
}

.flex-div-image-wrapper {
  flex: 0.5;
  justify-self: left;
}
.right {
  justify-content: left;
}

.left {
  justify-content: right;
}

.icon {
  max-height: 150px;
}

@media only screen and (max-device-width: 480px){
  .flex-div {
    flex-direction: column;
  }

  .left {
    flex-direction: column-reverse;
  }
}
</style>
  