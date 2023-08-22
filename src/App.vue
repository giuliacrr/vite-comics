<script>
import TheHeader from "./components/Header.vue";
import TheFooter from "./components/Footer.vue";
import TheShop from "./components/Shop.vue";
export default {
  components: {
    TheHeader,
    TheFooter,
    TheShop,
  },
};
</script>

<template>
  <TheHeader></TheHeader>
  <main></main>
  <TheShop></TheShop>
  <TheFooter></TheFooter>
</template>

<style lang="scss"></style>
