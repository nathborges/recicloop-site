<template>
  <div class="container-bag-bar">
    <div>
        <h2>Por que ser um estabelecimento parceiro do Recicloop?</h2>
    <div class="flexText"> 
      <div class="reasons">
        <p>Empresas e comércios que investem em projetos de reciclagem tem redução no imposto de renda, de acordo com a lei nº 6545/2019.</p>
      </div>
      <div class="reasons">
        <p>Maior trânsito de clientes em seu estabelecimento e consequentemente, mais vendas.</p>
      </div>
      <div class="reasons">
        <p>O estabelecimento poderá vender o lixo reciclável para empresas especializadas em coleta de recicláveis.</p>
      </div>

    </div>

    </div>
  </div>
</template>
  
  <script>
export default {
  name: "BusinessBar",
};
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .container-bag-bar {
        background-color: #003300;
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

    .flexText {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 10px;
    }

    .reasons {
      padding: 10px;
    }

    @media screen and (max-width: 992px) { 
      .flexText {
        flex-direction: column;
      }
    }
</style>
  