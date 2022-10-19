<template>
  <footer>
    <a
      class="social-link"
      href="https://www.facebook.com/profile.php?id=100063897079833"
      target="_blank"
    >
      <i class="bi bi-facebook"></i>
    </a>
    <p>
      Direitos reservados &copy; Eletro
      <span class="txt-blight"><i class="bi bi-lightning-fill"></i></span> Silva
    </p>
    <p>Desenvolvido por <span class="txt-blight">Felipe Carvalho</span></p>
  </footer>
</template>
<script>
export default {
  name: "FooterNav",
};
</script>
<style scoped>
footer {
  padding: 1.5rem 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.2rem;
  background-color: #010816;
  color: #fff;
  text-align: center;
}
.social-link {
  font-size: 2rem;
  color: #3759c2;
  padding-bottom: 1rem;
  text-decoration: none;
  transition: 0.6s;
}
.social-link:hover {
  color: #fff;
}
</style>
