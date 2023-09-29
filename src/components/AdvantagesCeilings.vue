<template>
  <div class="advantages">
    <h2 class="advantages-heading">
      <price-ceiling>Преимущества</price-ceiling> натяжных потолков
    </h2>
    <div class="advantages-box">
      <property-ceiling
        :advantage="advantages"
        style="display: grid; grid-template-columns: repeat(2, 4fr); gap: 40px"
      />
    </div>
  </div>
</template>

<script>
import PropertyCeiling from '@/components/TypeCeiling/PropertyCeiling';
export default {
  components: {
    PropertyCeiling,
  },
  data() {
    return {
      advantages: [
        {
          img: '../static/images/waterSvg.1b239ec6.svg',
          heading: 'Не затопят соседи',
          text: 'Потолки выдерживают до 100 литров воды на м2',
        },
        {
          img: '../static/images/waterSvg.svg',
          heading: 'Скорость установки',
          text: 'Монтаж потолка занимает 3 - 4 часа',
        },
        {
          img: '../img/waterSvg.1b239ec6.svg',
          heading: 'Долговечность',
          text: 'Со временем потолки не пожелтеют, не провиснут и не повредятся',
        },
        {
          img: '../img/waterSvg.1b239ec6.svg',
          heading: 'Простота ухода',
          text: 'Достаточно протирать мыльной водой один раз в 3 месяца',
        },
      ],
    };
  },
};
</script>

<style scoped>
.advantages {
  display: flex;
  justify-content: center;
  padding: 100px 0px;
  padding-right: 240px;
  padding-left: 140px;
}
.advantages-heading {
  color: #333;
  font-family: Rubik;
  font-size: 52px;
  font-style: normal;
  font-weight: 500;
  line-height: 64px;
  width: 400px;
}
.advantages-box {
  margin-left: 100px;
}
.advantages-box-up {
  display: flex;
  gap: 40px;
}
.advantages-box-down {
  display: flex;
  margin-top: 64px;
  gap: 40px;
}
</style>
