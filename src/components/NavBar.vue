<template>
  <div class="container">
    <img class="logo" src="../assets/logo_recicloop.svg">
  </div>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  display: flex;
  align-items: center;
  justify-items: start;
}
.logo {
  flex: 1;
  max-height: 50px;
  margin: 30px;
  justify-self: flex-start;
}
p {
  flex: 3;
  color: white;
}
</style>
