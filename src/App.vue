<script>
import TheHeader from "./components/Header.vue";
import TheHeroSec from "./components/HeroSec.vue";
import TheMainSec from "./components/MainComics.vue";
import dcComics from "./db/dc-comics.json";
import TheShop from "./components/Shop.vue";
import TheFooter from "./components/Footer.vue";

export default {
  components: {
    TheHeader,
    TheHeroSec,
    TheMainSec,
    TheShop,
    TheFooter,
  },
  data() {
    return {
      dcComics,
    };
  },
};
</script>

<template>
  <TheHeader></TheHeader>
  <TheHeroSec></TheHeroSec>
  <TheMainSec></TheMainSec>
  <TheShop></TheShop>
  <TheFooter></TheFooter>
</template>

<style lang="scss"></style>
