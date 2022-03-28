<template>
  <div class="container">
    <div class="midia">
      <p>Saks na mídia</p>

    </div>

    <div class="card">
      <div>
        <a href="">endeavor.org.br</a>
        <br>
        <br>
        <p>Saks é uma das empresas selecionadas no Scale-Up Endeavor 2022</p>
        <br><br><br><br>
        <a href="">Leia a matéria completa →</a>
      </div>
    </div>
    <div class="card">
      <a href="">braziljournal.com</a>
      <br>
      <b></b>
      <p>A Saks quer roubar mercado dos bancões na previdência. Os VCs estão dando força</p>
      <br><br><br><br>
      <a href="">Leia a matéria completa →</a>
    </div>
    <div class="card">
      <a href="">beyondthelaw.news</a>
      <br>

      <p>Digital Private Pension Broker Saks Lands BRL 26 Million Seed Investment from Itaú-Unibanco’s Private Equity Fund Kinea and Canary</p>
      <br><br>
      <a href="">Leia a matéria completa →</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Box10'
}
</script>

<style lang="css" scoped>
.container {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  width: 100vw;
  height: 55vh;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  flex-direction: row;
  flex-wrap: wrap;
}

.card {
  width: 24%;
  height: 45vh;
  display: flex;
  justify-items: center;
  align-items: center;
  padding: 5px 25px;
}

.midia {
  width: 100%;
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 32px;
  line-height: 110.2%;
  color: #272727;
  padding: 0px 25px;
}
</style>