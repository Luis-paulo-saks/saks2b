<template>
  <div class="container">
    <div class="texto">
      <h1>
        Saks, a primeira savetech da América latina
      </h1>
      <p>
        O jeito mais inteligente de oferecer previdência privada
      </p>

      <div>
        <a href="https://conteudo.hellosaks.com/saks2b-cadastro">
          <b-button variant="primary">Seja nosso parceiro</b-button>
        </a>
      </div>
    </div>
    <div class="imagem">
      <img src="../assets/header 2b.svg" alt="">
    </div>

    <div class="coteudomobile">

      <div class="flexdirection">

        <!-- 
        <div class="textomobile">
          <h1>
            Saks, a primeira savetech da América latina
          </h1>
        </div>
        -->
        <div class="imagemmobile">
          <div>
            <!-- <img src="../assets/happy-businesspeople-using-technology-devices-gadg-2021-08-29-06-50-51-utc 1.svg" alt="">
          -->
            <div class="textomobile">
              <h1>
                Saks, a primeira savetech da América latina
              </h1>
            </div>
          </div>
        </div>

      </div>

      <div class="texto-mobile">
        <p>O jeito mais inteligente de oferecer previdência privada</p>
      </div>

      <div class="button">
        <a href="https://conteudo.hellosaks.com/saks2b-cadastro">
          <button>Seja nosso parceiro</button>
        </a>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'Box1'
}
</script>

<style lang="css" scoped>
.container {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  width: auto;
  height: auto;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
  flex-wrap: nowrap;
}

.texto {
  width: 40%;
  height: 100%;
  display: flex;
  align-content: center;
  flex-direction: column;
  justify-content: center;
  padding: 50px;
}

.imagem {
  width: 40%;
  height: 100%;
}

.imagem img {
  width: 100%;
  height: 100%;
}

h1 {
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 700;
  font-size: 40px;
  line-height: 113.7%;
  color: #376fe3;
}

p {
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 124.7%;
  color: #131c2f;
  margin-top: 32px;
}

button {
  width: 329px;
  height: 78px;
  background: #376fe3;
  border-radius: 10px;
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 124.7%;
  color: #fbfbfb;
  margin-top: 32px;
}

.coteudomobile {
  display: none;
  flex-direction: column;
  height: auto;
}
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
/**************************************************************************************************************************************************************************************************************************************************************************************************************************************************** */
@media only screen and (max-width: 1024px) {
  .container {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    width: auto;
    height: auto;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
    flex-wrap: wrap;
  }

  .texto {
    display: none;
  }

  .imagem {
    display: none;
  }

  h1 {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 32px;
    line-height: 140.7%;
    color: #fbfbfb;
  }

  p {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 24px;
    line-height: 124.7%;
    color: #131c2f;
    margin-top: 32px;
  }

  button {
    width: 329px;
    height: 78px;
    background: #376fe3;
    border-radius: 10px;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 24px;
    line-height: 124.7%;
    color: #fbfbfb;
    margin-top: 32px;
  }

  .coteudomobile {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    align-items: center;
    height: auto;
  }
  /*
  .flexdirection {
    width: 100%;
    display: flex;
    flex-direction: row;
      align-items: center;
  }
*/
  .textomobile {
    background-color: #376fe3;
    width: 80%;
    height: 25vh;
    margin-left: 18%;
    margin-top: 40%;
    z-index: 1;
    padding: 8px;
    mix-blend-mode: multiply;
  }

  .imagemmobile {
    width: 100%;
    height: 100%;
    z-index: 2;
    mix-blend-mode: multiply;
    display: flex;
    justify-content: flex-end;
    z-index: 2;
    background: linear-gradient(
        0deg,
        rgba(5, 75, 220, 0.1),
        rgba(5, 75, 220, 0.1)
      ),
      url("../assets/happy-businesspeople-using-technology-devices-gadg-2021-08-29-06-50-51-utc 1.svg");

    padding: 25px;
    background-repeat: no-repeat;
    background-size: 140% 100%;
    top: 0;
    right: 0;
  }
  /*
  img {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: flex-end;
    flex-wrap: nowrap;
  }
*/
  .texto-mobile {
    width: 90%;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 124.7%;
    color: #131c2f;
    top: 20%;
    position: relative;
  }

  .button {
    /* width: 100%;
    height: 78px;
    background: #376fe3;*/
    border-radius: 10px;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 24px;
    line-height: 124.7%;
    color: #fbfbfb;
    margin-top: 32px;
    display: flex;
    align-items: center;
    justify-content: center;
    align-content: center;
  }
}
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/************************************************************************************************************************************************************************************************************ */
/*

@media only screen and (width: 768px) {
  .imagemmobile {
    width: 80%;
    height: 382px;
    z-index: 2;
    mix-blend-mode: multiply;
    position: absolute;
    right: 41px;
    top: 10vh;

    background: teal;
  }

  .textomobile {
    /* background-color: #376fe3; 
    background-color: red;
    width: 100%;
    margin-left: 10px;
    height: 31rem;
    display: flex;
    justify-content: center;
    align-content: center;
    align-items: center;
    z-index: 1;
    position: relative;
    top: 20%;
    left: 0%;
    padding: 8px;
  }

  h1 {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 32px;
    line-height: 140.7%;
    color: #fbfbfb;
  }

  .coteudomobile {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    align-items: center;
    height: 75rem;
  }

  .texto-mobile {
    width: 90%;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 124.7%;
    color: #131c2f;
    padding: 0px !important;
    margin: 0px !important;

    top: 25%;
    position: relative;
  }
  button {
    width: 100%;
  }

  .button {
    width: 90%;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 124.7%;
    color: #131c2f;
    padding: 0px !important;
    margin: 0px !important;
    top: 25%;
    bottom: 20%;
    position: relative;
  }
}

@media only screen and (max-width: 375px) {
  /* ou 390
  .container {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    width: auto;
    height: auto;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    flex-wrap: nowrap;
  }

  .texto {
    width: 50%;
    height: 100%;
    display: flex;
    align-content: center;
    flex-direction: column;
    justify-content: center;
    padding: 50px;
    display: none;
  }

  .imagem {
    display: none;
  }

  h1 {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 32px;
    line-height: 140.7%;
    color: #fbfbfb;
  }

  p {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 24px;
    line-height: 124.7%;
    color: #131c2f;
    margin-top: 32px;
  }

  button {
    width: 329px;
    height: 78px;
    background: #376fe3;
    border-radius: 10px;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 24px;
    line-height: 124.7%;
    color: #fbfbfb;
    margin-top: 32px;
  }

  .coteudomobile {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    align-items: center;
    height: auto;
  }

  .textomobile {
    background-color: #376fe3;
    width: 80%;
    margin-left: 10px;
    height: 16rem;
    display: flex;
    justify-content: center;
    align-content: center;
    align-items: center;
    z-index: 1;
    position: relative;
    top: 30%;
    left: 6%;
    padding: 8px;
  }

  .imagemmobile {
    width: 80%;
    height: 382px;
    z-index: 2;
    mix-blend-mode: multiply;
  }

  img {
    width: 300px;
    height: 100%;
    display: flex;
    justify-content: flex-end;
  }

  .flexdirection {
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
  }

  .texto-mobile {
    width: 90%;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 124.7%;
    color: #131c2f;
    padding: 0px !important;
    margin: 0px !important;
    background-color: blue;
    top: 20%;
    position: relative;
  }

  .button {
    width: 90%;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 124.7%;
    color: #131c2f;
    padding: 0px !important;
    margin: 0px !important;
    top: 20%;
    position: relative;
  }
}

*/
</style>