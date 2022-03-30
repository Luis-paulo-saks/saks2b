<template>
  <div>
    <div class="container">
      <div class="texto">
        <div>
          <img src="../assets/chapeu.svg" alt="">
          <br>
          <br>
        </div>
        <div>
          <p class="expecializado">Você vai receber treinamento e desenvolvimento especializado</p>
        </div>
        <div>
          <h4> O parceiro Saks tem acompanhamento completo do nosso time de treinamento e desenvolvimento. Desse jeito, você escala seu modelo de atendimento de um jeito simples. </h4>

        </div>
        <div>

          <h2 class="treinamentos"> Acesso aos treinamentos e Ferramentas da Saks: </h2>

          <ul>
            <li>Aplicativo</li>
            <li> Plataforma</li>
            <li> Produto previdência privada</li>
            <li>Planilhas Auxiliares</li>
            <li> Follow up de todos fundos disponíveis na plataforma</li>
          </ul>

          <h2 class="treinamentos"> Acompanhamento semanal nos 3 primeiros meses com:</h2>

          <ul>
            <li>Suporte para reuniões de fechamento</li>
            <li> Discurso de venda</li>
            <li> Estratégia de aquisição de clientes</li>
          </ul>

        </div>

        <div>
          <a href="https://conteudo.hellosaks.com/saks2b-cadastro">
            <b-button variant="primary">Seja nosso parceiro</b-button>
          </a>
        </div>
      </div>

      <div class="imagem">
        <img src="../assets/Group 816.png" alt="" class="desktop">

      </div>

    </div>

    <div class="containermobile">
      <div class="imagem">
        <img src="../assets/Group 816.png" alt="" class="desktop">

      </div>

      <div class="imagem-mobile">
        <img src="../assets/chapeumobile.svg" alt="">
        <p class="expecializado-mobile">Você vai receber treinamento e desenvolvimento especializado</p>

      </div>

      <div style=" background: #376fe3;">
        <div class="treinamentosMobile">
          <h4> O parceiro Saks tem acompanhamento completo do nosso time de treinamento e desenvolvimento. Desse jeito, você escala seu modelo de atendimento de um jeito simples. </h4>

        </div>

        <h2 class="treinamentosMobile"> Acesso aos treinamentos e Ferramentas da Saks: </h2>

        <ul>
          <li>Aplicativo</li>
          <li> Plataforma</li>
          <li> Produto previdência privada</li>
          <li>Planilhas Auxiliares</li>
          <li> Follow up de todos fundos disponíveis na plataforma</li>
        </ul>

        <h2 class="treinamentosMobile"> Acompanhamento semanal nos 3 primeiros meses com:</h2>

        <ul>
          <li>Suporte para reuniões de fechamento</li>
          <li> Discurso de venda</li>
          <li> Estratégia de aquisição de clientes</li>
        </ul>

      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'Box7'
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
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 64px;
}

.texto {
  width: 40%;
  height: 100%;
  padding: 32px;
}

.imagem {
  width: 60%;
  height: 100%;
}
.imagem img {
  width: 100%;
  height: 100%;
}

.expecializado {
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 40px;
  line-height: 99.7%;
  color: #131c2f;
}

.treinamentos {
  font-family: "DM Sans";
  font-weight: 700;
  font-size: 16px;
  line-height: 124.7%;
}

li {
  color: black;
}

h4 {
  font-size: 16px;
  color: #656565;
}

.mobile {
  display: none;
}
.containermobile {
  display: none;
}
@media only screen and (max-width: 1024px) {
  .container {
    display: none;
  }
  .containermobile {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    width: 100vw;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    background-color: #376fe3;
  }

  .texto {
    width: 100%;
    height: 100%;
    padding: 32px;
  }

  .imagem-mobile {
    width: 100%;
    height: 100%;
    background: #376fe3;
    mix-blend-mode: multiply;

    background-repeat: no-repeat;
  }

  .expecializado-mobile {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 32px;
    line-height: 99.7%;
    color: #ffffff !important;
    width: 80%;
    padding: 32px;
  }

  .treinamentos {
    font-family: "DM Sans";
    font-weight: 700;
    font-size: 16px;
    line-height: 124.7%;
  }

  .imagem {
    display: none;
  }

  .texto {
    display: none;
  }

  .imagem-mobile {
    width: 100%;
    height: 100%;
    min-height: 40vh;
    background: #376fe3;

    background-image: url("../assets/handsome-young-african-man-in-casual-clothing-usin-2022-02-04-03-04-49-utc 1.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-color: #376fe3;
  }
  .imagem-mobile img {
    padding: 32px;
    color: white;
    fill: white;
  }

  .treinamentosMobile {
    background: #376fe3;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 124.7%;
    color: #fbfbfb;
    text-align: center;
  }

  h4 {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 124.7%;
    /* or 20px */

    color: #fbfbfb;
    text-align: justify;
    padding: 16px;
    width: 100%;
  }
}
</style>