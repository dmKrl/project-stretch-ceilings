<template>
  <div class="projects">
    <heading-and-buttons>Наши проекты</heading-and-buttons>
    <item-project :items="items" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          img: '../../../static/images/ceiling1.png',
          nameCeiling: 'Матовый потолок в гостинной 52 м2',
          price: '20 500 ₽',
          collectionCanvas: 'EcoLine',
          profile: '11,9 м.л.',
          fastening: '3 шт',
          angles: '4 шт',
        },
        {
          img: '../../../static/images/ceiling1.png',
          nameCeiling: 'Многоуровневый потолок в гостинной 48 м2',
          price: '23 800 ₽',
          collectionCanvas: 'Descor',
          profile: '11,9 м.л.',
          fastening: '3 шт',
          angles: '8 шт',
        },
      ],
    };
  },
};
</script>

<style scoped>
.projects {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 100px 140px;
}
</style>
