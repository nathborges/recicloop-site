<template>
  <div class="container-bag-bar">
    <div>
        <h2>Como os pontos são calculados?</h2>
        <p>O estabelecimento parceiro disponibilizará três tamanhos de sacolas para o usuário descartar os recicláveis. Cada tamanho de sacola equivale a uma quantidade específica de pontos:</p>
    <div class="flexBags"> 
      <div>
        <img src="../assets/bag-amarela.png"/>
      </div>
      <div>
        <img src="../assets/bag-laranja.png"/>
      </div>
      <div>
        <img src="../assets/bag-azul.png"/>
      </div>

    </div>

    </div>
  </div>
</template>
  
  <script>
export default {
  name: "BagBar",
};
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .container-bag-bar {
      background-color: #002100;

        margin: 0;
        padding: 40px;
    }

    h2 {
        font-family: "arboria-bold";
        font-size: 40px;
        color: whitesmoke;
        margin: 0;
    }

      p {
        font-family: "arboria1";
        font-size: 30px;
        color: whitesmoke;
    }

    .flexBags {
      display: flex;
      align-items:baseline;
      justify-content: center;
    }

    .flexBags p {
      padding: 0;
      margin: 0;
    }

    .flexBags img {
      max-height: 400px;
    }

    @media screen and (max-width: 992px)  { 
      .flexBags {
        flex-direction: column;
      }
    }
</style>
  