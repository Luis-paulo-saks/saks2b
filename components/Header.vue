<!-- Please remove this file from your project -->
<template>
  <div class="container">
    <div class="logo">
      <a href="/"><img src="../assets/logo.svg" alt=""></a>
    </div>
    <div class="paginas">
      <div>
        <b-link href="https://hellosaks.com/sobre-nos">Sobre Nós</b-link>
      </div>
      <div>
        <b-link href="https://shots.hellosaks.com/?_gl=1%2Ahinu0p%2A_ga%2AMTUyODQ2NjcxNS4xNjQzMzA3NTU2%2A_ga_10XR2WQ0H1%2AMTY0ODQ3NzMyMS4zLjEuMTY0ODQ3NzgxMS41MA..">Shots </b-link>
      </div>
      <div>

        <b-link href="#foo"> <img src="../assets/Login.svg" alt=""></b-link>
      </div>
    </div>
    <div class="paginasmobile">
      <div>

        <b-button v-b-toggle="'collapse-2'" class="m-1"><img src="../assets/toggle.svg" alt=""></b-button>

        <!-- Element to collapse -->
        <b-collapse id="collapse-2">
          <b-card>
            <b-link href="https://hellosaks.com/sobre-nos">Sobre Nós</b-link>
          </b-card>
          <b-card>
            <b-link href="https://shots.hellosaks.com/?_gl=1%2Ahinu0p%2A_ga%2AMTUyODQ2NjcxNS4xNjQzMzA3NTU2%2A_ga_10XR2WQ0H1%2AMTY0ODQ3NzMyMS4zLjEuMTY0ODQ3NzgxMS41MA..">Shots </b-link>
          </b-card>
          <b-card>
            <b-link href="#foo"> <img src="../assets/Login.svg" alt=""></b-link>
          </b-card>
        </b-collapse>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtHeader'
}
</script>

<style lang="css" scoped>
.container {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  width: 100vw;
  height: 10vh;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  position: relative;
}

.logo {
  height: 10vh;
  width: 20vw;
  display: flex;
  align-items: center;
  justify-content: center;
}

.paginas {
  height: 10vh;
  width: 40vw;
  display: flex;
  align-items: center;
  display: flex;
  justify-content: space-around;
  align-items: center;
  font-family: "Sora";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 120%;
  display: flex;
  align-items: center;
  color: #0052fe;
}

.paginasmobile {
  display: none;
}

@media only screen and (max-width: 1024px) {
  .container {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    width: 100vw;
    height: 25vh;
    display: flex;
    flex-direction: row;
    justify-content: space-between;

    flex-wrap: wrap;
    align-content: flex-start;
    align-items: baseline;
  }
  .logo {
    height: 10vh;
    width: 50vw;
  }

  .paginasmobile {
    display: block;
  }

  .paginas {
    display: none;
  }

  b-card {
    padding: 0px !important;
    font-size: 8px !important;
  }
}
</style>