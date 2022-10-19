<template>
  <HeroBanner />
  <OurServices />
  <OurAddress />
  <FooterNav />
  <WppBtn />
</template>
<script>
import HeroBanner from "./components/HeroBanner.vue";
import OurServices from "./components/OurServices.vue";
import OurAddress from "./components/OurAddress.vue";
import FooterNav from "./components/FooterNav.vue";
import WppBtn from "./components/WppBtn.vue";
export default {
  name: "App",
  components: { HeroBanner, OurServices, OurAddress, FooterNav, WppBtn },
};
</script>
<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: Arial, Helvetica, sans-serif;
}
.txt-white {
  color: #fff;
}
.txt-blight {
  color: #3759c2;
}
.txt-bdark {
  color: #001c55;
}
.txt-gray {
  color: #8e93b0;
}
</style>
