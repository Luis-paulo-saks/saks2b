<template>
  <div class="container">
    <div class="text">
      <span>Veja o que nossos parceiros falaram sobre a Saks!</span>

    </div>

    <div class="Carousel">
      <div>
        <VueSlickCarousel v-bind="settings">
          <div class="card">
            <h3>Raízes Corretora:</h3>
            <br><br>
            <p>"Excelente solução tecnológica que certamente irá disruptar o mercado de previdência privada no Brasil. Considero que o modelo é bastante flexível e entrega solução muito interessante para clientes e parceiros."</p>
          </div>
          <div class="card">
            <h3>Andaluz:</h3>
            <br><br>

            <p>"A Saks sempre apresenta os melhores métodos para aumentar vendas e fidelizar os clientes e parceiros. Suporte impecável e uma parceria impar para nosso escritório."</p>
          </div>
          <div class="card">
            <h3>Norte seguro corretora de seguros:</h3>
            <br>

            <p>"Não conhecia a plataforma, a partir da primeira reunião já achei top! O suporte que a empresa dá aos corretores é excelente! Facilidade no processo da venda e ganho de tempo. Recomendo!"</p>

          </div>
          <div class="card">
            <h3>Gw9 Capital:</h3>
            <br>
            <br>
            <p>"O atendimento do suporte comercial com o Pedro e operacional com Jedson está sendo essencial para a construção dessa parceria."</p>
          </div>
          <div class="card">
            <h3>WN Consultoria:</h3>
            <br>
            <br>
            <p>"A Saks é uma boa parceira e está engajada na melhoria contínua dos processos."</p>
          </div>
          <div class="card">
            <h3>Gentil Lopes de Oliveira Junior</h3>
            <br>
            <p>"A proposta de trabalhar para a Saks abre uma excelente oportunidade para quem pretende se inserir ou dar continuidade no mercado de previdência. É uma plataforma moderna, de fácil operação, treinamentos eficazes e traz incentivos financeiros ainda não vistos no mercado."</p>
          </div>
          <div class="card">
            <h3>Gentil Lopes de Oliveira Junior</h3>
            <br>
            <p>"A Saks é uma grande sacada, parabéns aos idealizadores. Tenho certeza que se tornará uma referência no segmento e tornará a previdência privada um investimento ao alcance de muitos que ainda não conhecem ou dependem dos bancos tradicionais.
              Além de tornar o assessor (corretor de seguros) um agente importantíssimo no processo, que para isso deverá se especializar e ter muito conhecimento na área."
            </p>
          </div>
        </VueSlickCarousel>
      </div>
    </div>

    <div class="Carouselmobile">

      <div class="text-mobile">
        <span>Veja o que nossos parceiros falaram sobre a Saks!</span>

      </div>
      <div>
        <VueSlickCarousel v-bind="settingsmobile">
          <div class="card">
            <h3>Raízes Corretora:</h3>
            <br><br>
            <p>"Excelente solução tecnológica que certamente irá disruptar o mercado de previdência privada no Brasil. Considero que o modelo é bastante flexível e entrega solução muito interessante para clientes e parceiros."</p>
          </div>
          <div class="card">
            <h3>Andaluz:</h3>
            <br><br>

            <p>"A Saks sempre apresenta os melhores métodos para aumentar vendas e fidelizar os clientes e parceiros. Suporte impecável e uma parceria impar para nosso escritório."</p>
          </div>
          <div class="card">
            <h3>Norte seguro corretora de seguros:</h3>
            <br>

            <p>"Não conhecia a plataforma, a partir da primeira reunião já achei top! O suporte que a empresa dá aos corretores é excelente! Facilidade no processo da venda e ganho de tempo. Recomendo!"</p>

          </div>
          <div class="card">
            <h3>Gw9 Capital:</h3>
            <br>
            <br>
            <p>"O atendimento do suporte comercial com o Pedro e operacional com Jedson está sendo essencial para a construção dessa parceria."</p>
          </div>
          <div class="card">
            <h3>WN Consultoria:</h3>
            <br>
            <br>
            <p>"A Saks é uma boa parceira e está engajada na melhoria contínua dos processos."</p>
          </div>
          <div class="card">
            <h3>Gentil Lopes de Oliveira Junior</h3>
            <br>
            <p>"A proposta de trabalhar para a Saks abre uma excelente oportunidade para quem pretende se inserir ou dar continuidade no mercado de previdência. É uma plataforma moderna, de fácil operação, treinamentos eficazes e traz incentivos financeiros ainda não vistos no mercado."</p>
          </div>
          <div class="card">
            <h3>Gentil Lopes de Oliveira Junior</h3>
            <br>
            <p>"A Saks é uma grande sacada, parabéns aos idealizadores. Tenho certeza que se tornará uma referência no segmento e tornará a previdência privada um investimento ao alcance de muitos que ainda não conhecem ou dependem dos bancos tradicionais.
              Além de tornar o assessor (corretor de seguros) um agente importantíssimo no processo, que para isso deverá se especializar e ter muito conhecimento na área."
            </p>
          </div>
        </VueSlickCarousel>
      </div>
    </div>
  </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: 'Carousel',
  components: { VueSlickCarousel },
  data () {
    return {
      settings: {
        "dots": true,
        "infinite": false,
        "initialSlide": 0,
        "speed": 500,
        "slidesToShow": 3,
        "slidesToScroll": 1,
        "swipeToSlide": true,
        "arrows": true
      },
      settingsmobile: {
        "dots": true,
        "infinite": false,
        "initialSlide": 0,
        "speed": 500,
        "slidesToShow": 1,
        "slidesToScroll": 1,
        "swipeToSlide": true,
        "arrows": true
      },
    }
  }

}

</script>

<style lang="css" scoped>
.container {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  width: 100%;
  height: auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-content: stretch;
  justify-content: flex-start;
}

.text {
  display: flex;
  width: 100%;
  max-height: 10vh;
  flex-direction: row;
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 35px;
  line-height: 110.2%;
  color: #272727;
  padding: 55px 50px;
}

.Carousel {
  width: 100%;
  height: 200px;
}

.card {
  max-width: 70%;
  height: 55vh;
  display: flex;
  justify-items: center;
  align-items: center;
  padding: 35px 25px;
  flex-direction: row;
  align-items: center;
  background: #e9eefa;
  border-radius: 12px;
  margin-top: 30px;
}

div {
  text-align: center;
}
img {
  width: 100%;
}

h3 {
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 700;
  font-size: 20.898px;
  line-height: 110.2%;
  color: #272727;
}

p {
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 110.2%;
  color: #272727;
}

/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */
/***************************************************************************** */

.Carouselmobile {
  display: none;
}

@media only screen and (max-width: 1024px) {
  .Carousel {
    display: none;
  }
  .Carouselmobile {
    display: block;
  }
  .container {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    width: 100%;
    height: 100vh;
  }

  .text {
    display: none;
  }

  .text-mobile {
    display: flex;
    width: 100%;
    height: auto;
    flex-direction: row;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 35px;
    line-height: 110.2%;
    color: #272727;
    padding: 5px;
    margin: auto;
  }

  .Carousel {
    width: 100%;
    height: 200px;
  }

  .card {
    width: 70% !important;
    height: auto;
    min-height: 50vh;
    display: flex;
    justify-items: center;
    align-items: center;
    padding: 35px 25px;
    flex-direction: row;
    align-items: center;
    background: #e9eefa;
    border-radius: 12px;
    margin-top: 30px;
  }

  div {
    text-align: center;
  }
  img {
    width: 100%;
  }

  h3 {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 700;
    font-size: 20.898px;
    line-height: 110.2%;
    color: #272727;
  }

  p {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 110.2%;
    color: #272727;
  }
}
</style>