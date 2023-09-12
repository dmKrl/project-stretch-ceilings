<template>
  <div class="information">
    <div class="information-box">
      <h2 class="information-heading">
        Натяжные потолки с установкой за 24 часа по цене от
        <price-ceiling>150 ₽/м<sup>2</sup></price-ceiling>
      </h2>
      <information-about-ceiling />
      <button-price>Расчитать стоимость</button-price>
    </div>
    <div class="information-room">
      <img src="../static/images/mainRoom.jpg" alt="" class="information-img" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.information {
  display: flex;
  align-self: flex-end;
  justify-content: space-between;
  width: 100vw;
  margin-top: 20px;
}
.information-box {
  margin: 80px 0px 101px 120px;
  align-self: flex-start;
  font-family: Rubik;
  font-style: normal;
  line-height: normal;
  font-weight: 600;
  line-height: 60px;
}
.information-heading {
  color: var(--, #333);
  font-size: 3rem;
  max-width: 597px;
}
.information-room {
  display: flex;
  justify-content: flex-end;
  margin-left: 63px;
}
.information-img {
  max-width: 100%;
}
</style>
