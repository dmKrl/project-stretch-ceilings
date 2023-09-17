<template>
  <div class="vantage">
    <h2 class="vantage-heading">Как заказать</h2>
    <property-ceiling
      style="display: flex; gap: 40px; margin-top: 64px; flex-wrap: wrap; justify-content: center;"
      :advantage="vantage"
    />
  </div>
</template>

<script>
import PropertyCeiling from './TypeCeiling/PropertyCeiling';
export default {
  components: {
    PropertyCeiling,
  },
  data() {
    return {
      vantage: [
        {
          img: '/img/firstNum.405f7b30.svg',
          heading: 'Заявка',
          text: 'Оставьте заявку на сайте или позвоните нам по телефону +7 912 234-34-34',
        },
        {
          img: '/img/firstNum.405f7b30.svg',
          heading: 'Выезд замерщика',
          text: 'Менеджер сделает расчёт, согласует дату и время бесплатного замера',
        },
        {
          img: '/img/firstNum.405f7b30.svg',
          heading: 'Монтаж',
          text: 'В течение дня после замерак вам приедут мастера и проведут монтаж за 3-4 часа',
        },
        {
          img: '/img/firstNum.405f7b30.svg',
          heading: 'Приём работ',
          text: 'По факту выполнения работ вы оплачиваете заказ удобным для вас способом',
        },
      ],
    };
  },
};
</script>

<style scoped>
.vantage {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 100px 140px;
}
.vantage-heading {
  color: #333;
  font-family: Rubik;
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
</style>
