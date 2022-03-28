<template >
  <div class="container">
    <Header />
    <Box1 />
    <Box2 />
    <Box3 />
    <Box4 />
    <Box5 />
    <Box6 />
    <Box7 />
    <Box8 />
    <Box9 />
    <Box10 />
    <Box6 />
    <Carousel />
    <Footer />
  </div>
</template>

<script>


export default {

  name: 'IndexPage'
}
</script>

<style>
.container {
  box-sizing: border-box;
  min-width: 95vw;
  height: auto;
  display: flex;
  flex-direction: column;
  padding: 0px;
  margin: 0px 2%;
  justify-content: center;
  background: red;
}

@media only screen and (max-width: 1024px) {
  .container {
    box-sizing: border-box;
    width: 100vw;
    height: auto;
    display: flex;
    flex-direction: column;
    padding: 0px;
    margin: 0px 0%;
    justify-content: center;
    background: bisque;
  }
}
</style>
