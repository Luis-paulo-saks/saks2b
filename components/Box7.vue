<template>
  <div class="container">
    <div class="texto">
      <div>
        <img src="../assets/chapeu.svg" alt="">
        <br>
        <br>
      </div>
      <div>
        <p id="expecializado">Você vai receber treinamento e desenvolvimento especializado</p>
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
      <img src="../assets/Group 816.svg" alt="">
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
  flex-direction: row;
}

.texto {
  width: 50%;
  height: 100%;
  padding: 32px;
}

.imagem {
  width: 50%;
  height: 100%;
}

#expecializado {
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
  color: #376fe3;
}

h4 {
  font-size: 16px;
  color: #656565;
}
</style>