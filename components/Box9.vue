<template>
  <div>
    <div class="container">

      <div class="imagem">
        <div>
          <img src="../assets/smiling-asian-man-using-smartphone-at-home-sitting-2022-01-12-19-53-55-utc 1.svg" alt="">
        </div>
      </div>
      <div class="texto">
        <div>
          <img src="../assets/arrowupright.svg" alt="">
        </div>
        <div>
          <p>Ficou interessado? Simule qual pode ser a sua remuneração como parceiro Saks!</p>
        </div>
        <div class="button">
          <a href="https://conteudo.hellosaks.com/saks2b-cadastro">
            <button>SIMULE SUA REMUNERAÇÃO AGORA</button>
          </a>
        </div>
      </div>
    </div>

    <div class="containermobile">

      <div class="imagem">

        <div class="arrow">
          <img src="../assets/arrowupright.svg" alt="">
        </div>
        <div class="texto">
          <p>Ficou interessado? Simule qual pode ser a sua remuneração como parceiro Saks!</p>
          <div class="button">
            <a href="https://conteudo.hellosaks.com/saks2b-cadastro">
              <button>SIMULE SUA REMUNERAÇÃO AGORA</button>
            </a>
          </div>
        </div>

      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'Box9'
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
  justify-content: space-between;
  align-items: center;
  flex-direction: row;
}

.texto {
  background-color: #376fe3;
  width: 50%;
  height: 60vh;
  display: flex;
  padding: 50px;
  flex-direction: column;
  position: relative;
  left: -10rem;
  mix-blend-mode: multiply;
}

.imagem {
  width: 40%;
  height: 100%;
}

div p {
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 32px;
  line-height: 110.2%;
  color: #fbfbfb;
  margin-top: 16px;
}

.button {
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 700;
  font-size: 20px;
  line-height: 110.2%;
  text-align: center;
  color: #fbfbfb;
  width: 100%;
}

button {
  width: 100%;
  height: 70px;
  background: #131c2f;
  border-radius: 10px;

  font-family: "DM Sans";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 124.7%;
  color: #fbfbfb;
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
    height: auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-direction: row;
    display: block;
  }

  .texto {
    width: 100vw;
    height: 80vh;
    display: flex;
    align-content: center;
    padding: 50px;
    flex-direction: column;
    background-color: none;
    mix-blend-mode: inherit;
    background-color: inherit;
    position: relative;
    left: -0%;
    top: calc(25vh);
  }

  .texto p {
    display: flex;
    align-content: flex-end;
    align-items: flex-end;
    width: 75vw;
  }

  .imagem {
    width: 100%;
    height: 100vh;
    font-size: 16px;
    background-image: url("../assets/smiling-asian-man-using-smartphone-at-home-sitting-2022-01-12-19-53-55-utc 1.svg");
    background-repeat: no-repeat;
  }

  div p {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 32px;
    line-height: 110.2%;
    color: #fbfbfb;
    margin-top: 16px;
  }

  .button {
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 700;
    font-size: 20px;
    line-height: 110.2%;
    text-align: center;
    color: #fbfbfb;
    width: 100%;
  }

  button {
    text-align: center;
    width: calc(80vw);
    height: 70px;
    background: #131c2f;
    border-radius: 10px;
    font-family: "DM Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 124.7%;
    display: flex;
    color: #fbfbfb;
    background: #376fe3;
    border-radius: 10px;
    justify-content: center;
    align-items: center;
  }

  .arrow {
    display: flex;
    margin-left: calc(10vw);
  }
}
</style>