<template>
  <div class="container">

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

    <div class="imagem">
      <img src="../assets/phone.svg" alt="">
    </div>

    <div class="mobile">
      <div class="imagemmobile2">
        <img src="../assets/mobileicons.svg" alt="">
      </div>
      <div class="aplicativosaks">
        <div>
          <p>Aplicativo Saks: a previdência privada do futuro</p>

        </div>
        <div class="contratarplano">
          <p>Imagina contratar um plano de previdência privada em menos de 5 minutos… Com o app Saks isso é possível!</p>

        </div>
      </div>

      <div class="imagemmobile">
        <img src="../assets/phone.svg" alt="">
      </div>

      <div class="contratarplano">
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
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  width: 100vw;
  height: 100%;
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-between;
  align-items: center;
  flex-direction: row;
}

.imagem {
  width: 50%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.texto {
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

.mobile {
  display: none;
}

@media only screen and (max-width: 1024px) {
  .texto {
    display: none;
  }

  .imagem {
    display: none;
  }

  .mobile {
    display: block;
  }
  .container {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    width: 100vw;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
  }

  .imagemmobile {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  li {
    color: #376fe3;
  }

  .imagemmobile2 img {
    width: 96px;
    margin: 16px;
  }

  .aplicativosaks {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 32px;
    line-height: 124.7%;
    color: #376fe3;
    padding: 16px;
  }

  .contratarplano {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 124.7%;
    color: #131c2f;
    padding: 16px;
  }
}
</style>