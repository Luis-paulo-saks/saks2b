<template>
  <div>
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
        <br>
        <p>Digital Private Pension Broker Saks Lands BRL 26 Million Seed Investment from Itaú-Unibanco’s Private Equity Fund Kinea and Canary</p>
        <br><br>
        <a href="">Leia a matéria completa →</a>
      </div>
    </div>
    <div class="containermobile">
      <VueSlickCarousel v-bind="settings">
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
      </VueSlickCarousel>
    </div>

  </div>
</template>

<script>

import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: 'Box10',
  components: { VueSlickCarousel },
  data () {
    return {
      settings: {
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
  height: 55vh;
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

.containermobile {
  display: none;
}

@media only screen and (max-width: 1024px) {
  .container {
    display: none;
  }

  .containermobile {
    box-sizing: border-box;
    width: 100vw;
    height: auto;
    display: flex;
    flex-direction: column;
    padding: 0px;
    margin: 0px 0%;
    justify-content: center;
    margin: 10px;
  }

  .card {
    width: 90% !important;
    height: 50vh;
    display: flex;
    justify-items: center;
    align-items: center;
    justify-content: center;
    text-justify: center;
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
}
</style>