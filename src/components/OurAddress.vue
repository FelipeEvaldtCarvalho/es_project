<template>
  <section>
    <div class="text-container">
      <div class="title-box">
        <h1 class="title txt-blight">Contato</h1>
      </div>
      <p><i class="bi bi-telephone-fill"></i> (51) 3469 1434</p>
      <p><i class="bi bi-whatsapp"></i> (51) 991 745 225</p>
      <div class="title-box">
        <h1 class="title txt-blight">Nosso Endereço</h1>
      </div>
      <p>Av. Gen. Flores da Cunha, 4489</p>
      <p>Vila Bom Principio, Cachoeirinha - RS</p>
      <div class="title-box">
        <h1 class="title txt-blight">Horário de funcionamento</h1>
      </div>
      <p>Segunda a Sexta: 08h as 12h - 14h as 18h</p>
      <p>Sábado: 08h as 12h</p>
    </div>
    <div class="map-container">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3457.6099195764787!2d-51.07643508598328!3d-29.933130297699478!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x40b1b5982ce775d5!2sEletro%20Silva%20-%20Lavadora%2C%20Secadora%20e%20Microondas!5e0!3m2!1spt-BR!2sbr!4v1666141629387!5m2!1spt-BR!2sbr"
        width="90%"
        height="100%"
        style="border: 0"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
      ></iframe>
    </div>
  </section>
</template>
<script>
export default {
  name: "OurAddress",
};
</script>
<style scoped>
section {
  display: flex;
  width: 100%;
  background-color: #e9e9e9;
}
.text-container {
  display: flex;
  width: 50%;
  justify-content: center;
  flex-direction: column;
  margin: 5rem;
}
.text-container * {
  margin-bottom: 1.5rem;
}
.title-box {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin-bottom: 1.5rem;
}
.title {
  border-bottom: 8px #8e93b0 solid;
  padding-bottom: 0.5rem;
  font-size: 2.2rem;
}
.text-container p {
  font-size: 1.3rem;
}
.map-container {
  display: flex;
  justify-content: end;
  width: 50%;
  height: auto;
  padding: 5rem 5% 5rem 0;
}
iframe {
  margin: auto;
}
@media screen and (max-width: 810px) {
  .text-container {
    width: 50%;
    margin-right: 0;
  }
}
@media screen and (max-width: 670px) {
  section {
    flex-direction: column;
  }
  .text-container {
    padding: 0 1rem;
    width: 100%;
    align-items: center;
    text-align: center;
    justify-content: center;
    margin: 5rem auto 0 auto;
  }
  .map-container {
    width: 100%;
    padding: 0;
    border-bottom: 8px #3759c2 solid;
  }
  iframe {
    width: 100%;
    height: 50vh;
  }
}
@media screen and (max-width: 480px) {
  .text-container {
    margin: 2rem 0;
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
