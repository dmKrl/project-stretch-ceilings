<template>
  <div class="information-ceiling">
    <div class="information-props" :class="stylesBlock">
      <p class="information-specifications" :class="stylesText">Гарантия</p>
      <p class="information-text" :class="stylesText">
        10 лет на монтаж и материалы
      </p>
    </div>
    <div class="information-props">
      <p class="information-specifications" :class="stylesText">Скорость</p>
      <p class="information-text" :class="stylesText">
        Замер и монтаж за 24 часа
      </p>
    </div>
    <div class="information-props">
      <p class="information-specifications" :class="stylesText">Чистота</p>
      <p class="information-text" :class="stylesText">Убираем за собой мусор</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'information-about-ceiling',
  props: {
    stylesText: {
      type: String,
      required: true,
    },
    stylesBlock: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
.information-ceiling {
  display: flex;
  gap: 3rem;
  margin-top: 3rem;
}
.information-props {
  display: flex;
  flex-direction: column;
  max-width: 132px;
}
.information-specifications {
  font-family: Rubik;
  font-size: 1.2rem;
  font-style: normal;
  line-height: 18px;
  background-color: #528fef;
  background-image: linear-gradient(128deg, #615bd6 14.8%, #528fef 85.41%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.information-text {
  color: #333;
  font-family: Lato;
  font-size: 1rem;
  padding-top: 12px;
  font-weight: 500;
  line-height: normal;
}
.custom {
  color: white;
  -webkit-text-fill-color: white;
  text-align: center;
}
.custom-block {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
