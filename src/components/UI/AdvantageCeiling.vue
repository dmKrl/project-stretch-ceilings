<template>
  <div class="advantage">
    <div class="advantage-box">
      <img
        class="advantage-img"
        src="../../static/images/waterSvg.svg"
        alt=""
      />
      <h4 class="advantage-heading"><slot></slot></h4>
      <p class="advantage-text"><slot></slot></p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.advantage {
  width: 258px;
}
.advantage-box {
  display: flex;
  flex-direction: column;
  align-self: flex-start;
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
