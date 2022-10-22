<template>
  <div class="container-about-us">
    <div>
        <h2>O que é o Recicloop?</h2>
        <p>O Recicloop é um aplicativo que busca democratizar o acesso a reciclagem no Brasil. A ideia é conectar pessoas que não tem `fácil acesso a reciclagem em sua vizinhança, com comércios que buscam aumentar o fluxo de clientes. Através do recicloop, além de poder ajudar o planeta dando a destinação correta para os resíduos, o usuário terá a chance de acumular pontos e resgatar recompensas.  </p>
    </div>
  </div>
</template>
  
  <script>
export default {
  name: "AboutBar",
};
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .container-about-us{
        background-color: green;
        margin: 0;
        padding: 40px;
    }

    .container-about-us h2 {
        font-family: "arboria-bold";
        font-size: 40px;
        color: whitesmoke;
        margin: 0;
    }

    .container-about-us p {
        font-family: "arboria1";
        font-size: 30px;
        color: whitesmoke;
    }
</style>
  