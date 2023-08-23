<script>
import dcComics from "../db/dc-comics.json";
import comicsCard from "./ComiCard.vue";
export default {
  components: {
    comicsCard,
  },
  data() {
    return {
      dcComics,
    };
  },
};
</script>

<template>
  <div>
    <div class="container position-relative">
      <div class="position-absolute position-set">
        <button class="text-uppercase fw-bold fs-4 p-3" type="button">
          current series
        </button>
      </div>
      <!--Comics-->
      <div>
        <div class="row row-cols-6 custom-style">
          <div v-for="(Comic, i) in dcComics">
            <comicsCard :thumb="Comic.thumb" :title="Comic.series">
            </comicsCard>
          </div>
        </div>
      </div>
      <div class="text-center mb-3">
        <button class="text-uppercase fw-bold fs-6 p-2" type="button">
          show more
        </button>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  background-color: #1c1c1c;
  button {
    border: none;
    background-color: #0282f9;
    color: white;
  }
  button:hover {
    background-color: white;
    color: #0282f9;
    cursor: pointer;
  }
}

.custom-style {
  padding-top: 60px;
  padding-bottom: 26px;
}

.position-set {
  top: -34px;
  left: -5px;
}
</style>
