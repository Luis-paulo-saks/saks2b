<template>
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
</template>

<script>
export default {
  name: 'Box9'
}
</script>

<style lang="css" scoped>
.container {
  background-color: black;
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
  background-color: #376fe3;
  width: 50%;
  height: 60vh;
  display: flex;
  padding: 50px;
  flex-direction: column;
  position: relative;
  left: -10rem;
}

.imagem {
  background-color: cadetblue;
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
</style>