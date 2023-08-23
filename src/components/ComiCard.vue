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
  <div class="mt-1 mb-3">
    <span class="comic-name text-white text-uppercase">{{ title }}</span>
  </div>
</template>

<style lang="scss" scoped>
img {
  height: 190px;
  width: 190px;
  object-fit: cover;
  object-position: top;
}

.comic-name {
  font-size: 0.8rem;
}
</style>
