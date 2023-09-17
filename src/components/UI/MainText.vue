<template>
  <div>
    <p class="main-text"><slot></slot></p>
  </div>
</template>

<script>
export default {
  name: 'main-text'
};
</script>

<style scoped>
.main-text {
  color: rgba(51, 51, 51, 0.8);
  font-family: Lato;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 26px;
}
</style>
