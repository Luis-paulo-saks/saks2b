<template>
  <div class="container">

    <div class="imagem">
      <img src="../assets/phone.svg" alt="">
    </div>
    <div class="texto">
      <div>
        <img src="../assets/mobileicons.svg" alt="">
      </div>
      <div>
        <p>Aplicativo Saks: a previdência privada do futuro</p>
      </div>
      <div>
        <p>Imagina contratar um plano de previdência privada em menos de 5 minutos… Com o app Saks isso é possível!</p>
        <p>E essa é só uma das funcionalidades. Tem muito mais:</p>

        <ul>
          <li>Faça contribuições extras;</li>
          <li>Acompanhe o rendimento do seu dinheiro;</li>
          <li>Faça a portabilidade sem sair de casa;</li>
          <li>Acompanhe os pagamentos;</li>
          <li>Crie objetivos e acompanhe a evolução deles.</li>
        </ul>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Box8'
}
</script>

<style lang="css" scoped>
.container {
  background-color: black;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  width: 100vw;
  height: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  flex-direction: row;
}

.imagem {
  background-color: cadetblue;
  width: 50%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.texto {
  background-color: blueviolet;
  width: 50%;
  height: 100%;
  display: flex;
  padding: 36px;
  display: flex;
  flex-direction: column;
}

li {
  color: #376fe3;
}
</style>