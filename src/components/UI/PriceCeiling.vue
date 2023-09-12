<template>
  <span
    ><strong class="information-heading-price"><slot></slot></strong
  ></span>
</template>

<script>
export default {
  name: 'price-ceiling',
};
</script>

<style scoped>
.information-heading-price {
  background-color: #528fef;
  background-image: linear-gradient(128deg, #615bd6 14.8%, #528fef 85.41%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-family: Rubik;
  font-size: 3rem;
  font-style: normal;
}
</style>
