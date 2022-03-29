<template>
  <div>
    <div class="container">
      <div class="divlogo">
        <div class="logo">
          <img src="../assets/logosaks.svg" alt="">
        </div>
        <div class="mobile">
          <img src="../assets/facebook.svg" alt="">
          <img src="../assets/tw.svg" alt="">
          <img src="../assets/insta.svg" alt="">
          <img src="../assets/lin.svg" alt="">
          <img src="../assets/yt.svg" alt="">
        </div>
      </div>
      <div class="divmobilecorretoras">
        <div class="mobileinfo">
          <div class="mobileicons">
            <img src="../assets/macimg.svg" alt="">
            <img src="../assets/playimg.svg" alt="">
          </div>
          <div class="mobiletext">
            <p>Beixe o app</p>
            <p>Disponivel em Apple App Store</p>
            <p>Disponivel em Google Play Store</p>
          </div>
        </div>

        <div class="seguradoras">
          <img src="../assets/zurich.svg" alt="">
          <img src="../assets/sul america.svg" alt="">
          <img src="../assets/icatu.svg" alt="">
        </div>

      </div>
      <div class="divtexto">
        <p>A Saks Consultoria, Assessoria, Vida e Previdência Ltda, é a Corretora de Seguros e Previdência que mais ajuda as pessoas a organizar as metas e guardar dinheiro pro futuro. O nosso CNPJ é o 11.094.618/0001-84 e a gente é Regulado e possui o código 202097936 na SUSEP. Nosso escritório fica na Cobertura do Edifício Sky Business Center na rua 1500, 820 Centro, Balneário Camboriú/SC – CEP 88.330.526. Quando vier para a praia, aparece aqui com a gente! :) </p>
        <p>© Copyright 2021. All Rights Reserved Saks.</p>
      </div>
    </div>
    <div class="containermobile">
      <div class="footermobile">
        <div class="logo2">
          <img src="../assets/logosaks.svg" alt="">
        </div>
        <div class="mobileinfo2">
          <div class="mobileicons2">
            <img src="../assets/macimg.svg" alt="">
            <img src="../assets/playimg.svg" alt="">
          </div>

        </div>
        <div class="mobiletext2">
          <p>Beixe o app</p>
          <p>Disponivel em Apple App Store</p>
          <p>Disponivel em Google Play Store</p>
        </div>
      </div>
      <div class="mobile">
        <img src="../assets/facebook.svg" alt="">
        <img src="../assets/tw.svg" alt="">
        <img src="../assets/insta.svg" alt="">
        <img src="../assets/lin.svg" alt="">
        <img src="../assets/yt.svg" alt="">
      </div>
      <div class="links">
        <a href="">Sobre nós</a>
        <a href="">Termos de uso</a>
        <a href="">Calculadora</a>
        <a href="">Baixe nosso e-book</a>
        <a href="">blog</a>
        <a href="">Faça portabilidade</a>

      </div>
      <div style="width:100%" class="contato">
        <img src="" alt="">
        <p>0800 878 0227</p>
        <p>help@hellosaks.com</p>
        <p>Atendimento das 9h as 18h (dias uteis)</p>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Carrousel'
}
</script>

<style lang="css" scoped>
.container {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  width: 100vw;
  height: 70vh;
  display: flex;
  flex-direction: row;
  align-items: center;
  flex-wrap: wrap;
}

.divlogo {
  background-color: indigo;
  width: 50%;
  height: 60%;
}

.divmobilecorretoras {
  width: 50%;
  height: 60%;
  background: yellow;
}

.divtexto {
  width: 100%;
  height: 40%;
  padding: 50px;
  background-color: tomato;
}

.logo {
  padding: 32px;
}

.mobile {
  padding: 32px 0px;
  display: flex;
  justify-content: space-evenly;
}

.mobileicons {
  width: 30%;
  background: gray;
  padding: 32px;
  height: 100%;
  text-align: center;
}

.mobiletext {
  width: 70%;
  padding: 32px;
  height: 100%;
  background: crimson;
  box-sizing: border-box;
  line-height: 10%;
  font-size: 12px;
}

.mobileinfo {
  display: flex;
  flex-direction: row;
  height: 50%;
}

.seguradoras {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  height: 50%;
  background-color: aqua;
}

.containermobile {
  display: none;
}

@media only screen and (max-width: 1024px) {
  .container {
    display: none;
  }
  .mobiletext {
    display: none;
  }

  .containermobile {
    display: block;
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    background: #0c0e12;
  }

  .footermobile {
    width: 100%;
    background: #0c0e12;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }
  .footermobile img {
    height: 35px;
  }

  .logo2 {
    width: 30%;
    display: flex;
    flex-direction: row;
    text-align: center;
    justify-content: center;
    align-items: center;
    padding: 2%;
  }

  .mobileinfo2 {
    width: 30%;
    display: flex;
    flex-direction: row;
    text-align: center;
    justify-content: center;
    align-items: center;
  }

  .mobiletext2 {
    width: 48%;
    display: flex;
    flex-direction: column;
    text-align: center;
    justify-content: center;
    align-items: center;

    color: #000;
  }

  .mobiletext2 p {
    font-size: 10px;
    line-height: 90%;
    color: white;
  }

  .mobile {
    background: #0c0e12;
  }

  .links {
    display: flex;
    flex-direction: column;
    padding: 16px;
  }

  .contato {
    color: white;
    padding: 16px;
  }
}
</style>