<template>
  <div class="logo">
    <div class="logo-up">
      <img class="logo-img" src="../../static/images/iconHouse.svg" alt="" />
      <h4 class="logo-heading">Ceiling+</h4>
    </div>
    <p class="logo-text">Натяжные потолки в Казани</p>
  </div>
</template>

<script>
export default {
  name: 'my-logo',
};
</script>

<style>
.logo {
  display: flex;
  flex-wrap: wrap;
  width: 223px;
  font-style: normal;
  line-height: normal;
}
.logo-img {
  width: 20px;
  height: 20px;
}
.logo-up {
  display: flex;
}
.logo-heading {
  color: #000;
  font-family: Inter;
  font-size: 1.5rem;
  font-weight: 700;
}
.logo-text {
  color: #808080;
  font-family: Inter;
  font-size: 1rem;
  font-weight: 400;
}
</style>
