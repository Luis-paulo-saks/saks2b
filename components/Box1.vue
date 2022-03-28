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
        <div class="textomobile">
          <h1>
            Saks, a primeira savetech da América latina
          </h1>
        </div>
        <div class="imagemmobile">
          <div>
            <img src="../assets/happy-businesspeople-using-technology-devices-gadg-2021-08-29-06-50-51-utc 1.svg" alt="">
          </div>
        </div>

      </div>
      <div class="texto-mobile">
        <p>O jeito mais inteligente de oferecer previdência privada</p>
      </div>
      <div>
        <a href="https://conteudo.hellosaks.com/saks2b-cadastro">
          <b-button variant="primary">Seja nosso parceiro</b-button>
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
  width: 50%;
  height: 100%;
  display: flex;
  align-content: center;
  flex-direction: column;
  justify-content: center;
  padding: 50px;
}

.imagem {
  width: 50%;
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
}

@media only screen and (max-width: 1024px) {
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
    width: 50%;
    height: 100%;
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
  }

  .textomobile {
    width: auto;
    background-color: #376fe3;
    height: 250px;
    padding: 8px;
    position: relative;
    left: 20%;
    display: flex;
    justify-content: center;
    align-content: center;
    align-items: center;
    z-index: 1;
    mix-blend-mode: multiply;
  }

  .imagemmobile {
    width: 482px;
    height: 500px;
    z-index: 2;
    display: flex;
    mix-blend-mode: multiply;
    border-radius: 0px;
    position: relative;
  }

  .coteudomobile img {
    width: 100%;
    position: relative;
    right: 4rem;
  }

  .flexdirection {
    display: flex;
    flex-direction: row;
    align-items: center;
  }

  .texto-mobile {
    width: 60%;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 124.7%;
    color: #131c2f;
    padding: 0px !important;
    margin: 0px !important;
  }
}
</style>