<template>
  <header>
    <h1 class="txt-white logo">
      Eletro
      <span class="txt-blight"><i class="bi bi-lightning-fill"></i></span> Silva
    </h1>
    <h2 class="txt-white">
      Serviço <span class="txt-blight">Especializado</span>
    </h2>
    <div class="brands">
      <img src="../../public/imgs/consul-logo.png" alt="consul" />
      <img src="../../public/imgs/brastemp-logo.png" alt="brastem" />
      <img src="../../public/imgs/electrolux-logo.png" alt="electrolux" />
    </div>
    <h2 class="txt-white">
      Desde <span class="txt-blight">1995</span> prestando serviço de
      <span class="txt-blight">qualidade</span>
    </h2>
  </header>
</template>
<script>
export default {
  name: "HeroBanner",
};
</script>
<style scoped>
header {
  display: flex;
  height: 100vh;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  background: url("../../public/imgs/heroback.png") no-repeat center
    center/cover;
  text-align: center;
  padding: 1rem;
}
.logo {
  font-size: 4rem;
}
h2 {
  font-weight: 100;
  font-size: 2.2rem;
}
.brands {
  display: flex;
  width: 100%;
  align-items: center;
  justify-content: center;
  gap: 3rem;
}
.brands img {
  width: 25%;
}
@media screen and (max-width: 480px) {
  .logo {
    font-size: 2.4rem;
  }
  h2 {
    font-size: 1.4rem;
  }
  .brands {
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 2rem;
  }
  .brands img {
    width: 50%;
  }
}
</style>
