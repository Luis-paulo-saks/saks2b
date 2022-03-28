<template>
  <div class="container">
    <div class="imagem">
      <img src="../assets/Rectangle 428.svg" alt="">
    </div>
    <div class="texto">
      <div>
        <p>Clique <a href="https://conteudo.hellosaks.com/saks2b-cadastro">AQUI.</a> </p>
      </div>
      <div>
        <img class="img" src="../assets/arrowdown.svg" alt="">
        <br>
        <br>
      </div>
      <div>
        <p>Preencha seus dados.</p>
      </div>
      <div>
        <img class="img" src="../assets/arrowdown.svg" alt="">
        <br>
        <br>
      </div>
      <div>
        <p>Nós agendamos uma reunião e fazemos a apresentação da proposta!</p>
      </div>
      <div>
        <img class="img" src="../assets/arrowdown.svg" alt="">
        <br>
        <br>
      </div>
      <div>
        <p>Parceria fechada: é hora de assinar o contrato.</p>
      </div>
      <div>
        <img class="img" src="../assets/arrowdown.svg" alt="">
        <br>
        <br>
      </div>
      <div>
        <p>Pronto, você pode começar a distribuir a previdência privada Saks.</p>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'Box5'
}
</script>

<style lang="css" scoped>
.container {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  flex-direction: row;
}

.texto {
  width: 50%;
  height: 81.5%;
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 124.7%;
  display: flex;
  text-align: center;
  color: #131c2f;
  flex-direction: column;
  padding: 32px;
}

a {
  color: #376fe3;
  text-decoration: underline;
}
.imagem {
  width: 50%;
  height: 100%;
}

.img {
  width: 25.38px;
  height: 25.38px;
}

img {
  width: 100%;
  height: 100%;
}
</style>