<template>
  <div class="vantage">
    <h2 class="vantage-heading">Преимущества работы с нами</h2>
    <property-ceiling
      style="
        display: flex;
        gap: 40px;
        margin-top: 64px;
        flex-wrap: wrap;
        justify-content: center;
      "
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
          img: '/img/waterSvg.1b239ec6.svg',
          heading: 'Скорость и чистота',
          text: 'Установим потолок за 3—4 часа и уберем после себя мусор',
        },
        {
          img: '/img/waterSvg.1b239ec6.svg',
          heading: 'Работаем без выходных',
          text: 'Наши мастера приедут замерить и установить потолки в любое удобное для вас время',
        },
        {
          img: '/img/waterSvg.1b239ec6.svg',
          heading: 'Гарантия 10 лет',
          text: 'Если что-то случится с потолком, мастера заменят его бесплатно',
        },
        {
          img: '/img/waterSvg.1b239ec6.svg',
          heading: 'Качество материалов',
          text: 'Работаем только с лучшими европейскими материалам Eiro MSD, Pong, Descor',
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
  background: #f4f4f4;
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
