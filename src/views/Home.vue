<template>
  <div class="home">
    <HeaderSpartShop />
    <HeroSpartShop />
    <BennerSpartShop />
    <InstaSpartShop />
    <PartnerSpartShop />
    <FooterSpartShop />
    
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderSpartShop from "@/components/HeaderSpartShop.vue";
import HeroSpartShop from "@/components/HeroSpartShop.vue";
import BennerSpartShop from "@/components/BennerSpartShop.vue";
import InstaSpartShop from "@/components/InstaSpartShop.vue";
import PartnerSpartShop from "@/components/PartnerSpartShop.vue";
import FooterSpartShop from "@/components/FooterSpartShop.vue";


export default {
  name: "Home",
  components: {
    HeaderSpartShop,
    HeroSpartShop,
    BennerSpartShop,
    InstaSpartShop,
    PartnerSpartShop,
    FooterSpartShop,
    
  },
};
</script>
