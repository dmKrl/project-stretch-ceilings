<template>
  <div class="type-box">
    <div class="type-backscreen"></div>
    <div class="type-swipper"></div>
    <div class="type-discription">
      <h3 class="type-discription-heading">Многоуровневые потолки</h3>
      <price-ceiling>200 ₽/м<sup>3</sup></price-ceiling>
      <p class="type-discription-text">
        Благодаря конструкции позволяют комбинировать цвета и фактуру потолка.
        <br />
        <span
          >Функционально разделяет комнату на зоны для сна, отдыха и рабочего
          места.</span
        >
      </p>
      <button-price>Рассчитать стоимость</button-price>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.type-box {
  width: min(1229px, 87%);
  height: min(992px, 100%);
  margin-top: 48px;
  margin-bottom: 100px;
  position: relative;
}
.type-swipper {
  position: absolute;
  background-image: url(../../static/images/typeCeiling.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  left: 0;
  top: 24px;
  width: 761px;
  height: 494px;
}

.type-backscreen {
  position: absolute;
  background: #7772eb;
  right: 0;
  top: 0;
  width: 709px;
  height: 461px;
}

.type-discription {
  position: absolute;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  background: #fff;
  bottom: 0;
  right: 197px;
  padding: 48px;
  width: 412px;
  height: 527px;
}
.type-discription-heading {
  color: #333;
  font-family: Rubik;
  font-size: 36px;
  font-style: normal;
  font-weight: 500;
  line-height: 44px;
}
.type-discription-text {
  margin-top: 20px;
  margin-bottom: 32px;
  color: #333;
  font-family: Lato;
  font-size: 1.2rem;
  font-style: normal;
  font-weight: 400;
}
</style>
