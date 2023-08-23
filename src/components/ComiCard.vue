<script>
export default {
  props: {
    thumb: String,
    title: String,
  },
};
</script>

<template>
  <!--immagine-->
  <div class="img"><img :src="thumb" alt="comic" /></div>
  <!--titolo-->
  <div class="mt-2">
    <span class="fs-6 text-white text-uppercase">{{ title }}</span>
  </div>
</template>

<style lang="scss" scoped>
img {
  height: 190px;
  width: 190px;
  object-fit: cover;
  object-position: top;
}
</style>
