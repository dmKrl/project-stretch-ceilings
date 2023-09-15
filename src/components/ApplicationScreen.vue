<template>
  <div class="application">
    <div class="application-container">
      <img class="application-img" src="../static/images/master.png" alt="" />
      <div class="application-box">
        <h2 class="appliction-heading">
          Оставьте заявку
          <price-ceiling><br />на бесплатный замер</price-ceiling>
        </h2>
        <main-text-in-project style="margin-top: 24px"
          >Замерщик приедет в течение двух часов, поможет с выбором цвета,
          фактуры и рассчитает окончательную стоимость</main-text-in-project
        ><br />
        <button-price>Рассчитать стоимость</button-price>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.application {
  display: flex;
  align-items: flex-end;
  justify-content: center;
  background: #f4f4f4;
  position: relative;
}
.application-container {
    max-width: 1440px;
}
.application-img {
  position: absolute;
  bottom: 0;
  left: 20vw;
}
.application-heading {
  color: #333;
  font-family: Rubik;
  font-size: 52px;
  font-style: normal;
  font-weight: 500;
  line-height: 60px;
  max-width: 563px;
}
.application-box {
  margin: 64px 235px 167px 624px;
  max-width: 563px;
}
</style>
