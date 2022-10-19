<template>
  <section>
    <div class="text-container">
      <div class="title-box">
        <h1 class="title txt-blight">Nossos Serviços</h1>
      </div>
      <p>
        Oferecemos mão de obra especializada para manutenção de lavadoras de
        roupa, microondas e secadoras das principais marcas do mercado.
      </p>
      <p>Para orçamentos em microondas traga seu equipamento até nossa loja.</p>
      <p>
        Para orçamento em sua máquina de lavar e secar, basta agendar uma visita
        técnica que iremos atende-lo em sua casa.
      </p>
      <p>
        Temos nossa loja onde vendemos peças e acessórios para seus
        eletrodomésticos.
      </p>
      <p>Visitas técnicas em Cachoeirinha e Gravataí.</p>
    </div>
    <div class="img-container">
      <img src="../../public/imgs/fixing.png" alt="Técnico" />
    </div>
  </section>
</template>
<script>
export default {
  name: "OurServices",
};
</script>
<style scoped>
section {
  display: flex;
  width: 100%;
  align-items: end;
}
.text-container {
  display: flex;
  width: 60%;
  justify-content: center;
  flex-direction: column;
  margin: 5rem 5rem;
  align-self: center;
}
.text-container * {
  margin-bottom: 1.5rem;
}
.title-box {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin-bottom: 2rem;
}
.title {
  border-bottom: 8px #8e93b0 solid;
  padding-bottom: 0.5rem;
  font-size: 2.2rem;
}
.text-container p {
  font-size: 1.3rem;
}
.img-container {
  display: flex;
  justify-content: end;
  width: 40%;
  height: 100%;
}
.img-container img {
  max-height: 90vh;
  width: 100%;
}
@media screen and (max-width: 810px) {
  .text-container {
    width: 100%;
    text-align: center;
    align-items: center;
  }
  .img-container {
    position: absolute;
    height: initial;
    z-index: -1;
    right: 0px;
    filter: opacity(0.5);
  }
}
@media screen and (max-width: 480px) {
  .text-container {
    margin: 2rem;
  }
  .title {
    font-size: 1.5rem;
    padding-bottom: 0.3rem;
    border-bottom: 5px #8e93b0 solid;
  }
  .text-container p {
    font-size: 1.2rem;
  }
}
</style>
