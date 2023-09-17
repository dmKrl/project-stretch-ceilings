<template>
  <div class="advantage">
    <div class="advantage-box" v-for="advantager in advantage">
      <img class="advantage-img" :src="advantager.img" alt="" />
      <h3 class="advantage-heading">
        <slot>{{ advantager.heading }}</slot>
      </h3>
      <main-text style="padding-top: 1rem">{{ advantager.text }}</main-text>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    advantage: {
      type: Array,
      required: true,
    },
  },
};
</script>

<style scoped>
.advantage-img {
  width: 4.5rem;
  height: 4.5rem;
}
.advantage-box {
  width: 258px;
}
.advantage-heading {
  margin-top: 32px;
  color: #333;
  font-family: Rubik;
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.advantage-text {
  color: rgba(51, 51, 51, 0.8);
  font-family: Lato;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 26px;
}
</style>
