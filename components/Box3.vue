<template>
  <div class="container">
    <div class="Card">
      <img src="../assets/moneyicon.svg" alt="">
      <br>
      <p>Melhor acordo comercial e remuneração diferenciada.</p>
      <br>

    </div>
    <div class="Card">

      <img src="../assets/Vector (1).svg" alt="">
      <br>
      <p>Contratação em menos de 5 minutos através do link de indicação.</p>
      <br>

    </div>
    <div class="Card">
      <img src="../assets/Group.svg" alt="">
      <br>
      <p>Experiência 100% digital.
        Você faz tudo pelo app.</p>
      <br>

    </div>

    <div class="Card">
      <img src="../assets/smile.svg" alt="">
      <br>
      <p>Reduza o backoffice: nós fazemos ele por você!</p>
      <br>

    </div>
    <div class="Card">
      <img src="../assets/medal.svg" alt="">
      <br>
      <p>Treinamento e desenvolvimento com o nosso time especializado.</p>
      <br>

    </div>
    <div class="Card">
      <img src="../assets/avatar.svg" alt="">
      <br>
      <p>Acesse todos seus clientes pela plataforma Saks.</p>
      <br>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Box3'
}
</script>

<style lang="css" scoped>
.container {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  width: 100vw;
  height: auto;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 124.7%;
  color: #376fe3;
  flex-wrap: wrap;
}

img {
  width: 32px;
  height: 32px;
}

.Card {
  width: 30%;
  height: auto;
  display: flex;
  align-items: left;
  flex-direction: column;
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 124.7%;
  color: #376fe3;
  background: #f3f3f3;
  border-radius: 10px;
  margin: 1%;
  padding: 2%;
}

@media only screen and (max-width: 1024px) {
  .container {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    width: 100vw;
    height: auto;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 124.7%;
    color: #376fe3;
    flex-wrap: wrap;
    padding: 5px;
  }

  img {
    width: 28px;
    height: 28px;
  }

  .Card {
    width: 90%;
    height: 80px;
    display: flex;
    align-items: left;
    flex-direction: row;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 124.7%;
    color: #131c2f;
    border-radius: 10px;
    justify-content: space-evenly;
    padding: 12px;
    margin: 1px;
  }
  p {
    width: 80%;
  }
}
</style>