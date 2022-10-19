<template>
  <a
    href="https://api.whatsapp.com/send?phone=5551991745225&text=Ol%C3%A1%2C%20tudo%20bem%3F"
    target="_blank"
  >
    <img src="../../public/imgs/wppbtn.png" alt="wpp" />
  </a>
</template>
<script>
export default {
  name: "WppBtn",
};
</script>
<style scoped>
a {
  position: fixed;
  bottom: 2rem;
  right: 2rem;
}
a img {
  height: 3.5rem;
}
@media screen and (max-width: 480px) {
  a {
    bottom: 1.5rem;
    right: 1.5rem;
  }
  a img {
    height: 3rem;
  }
}
</style>
