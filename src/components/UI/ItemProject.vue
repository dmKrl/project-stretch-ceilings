<template>
  <!-- Исправить ошибку оторбажения картинок -->
  <div class="swipper">
    <div class="swipper-item" v-for="item in items">
      <img class="swipper-image" :src="item.image" alt="" />
      <p class="swipper-name">{{ item.nameCeiling }}</p>
      <p class="swipper-price">{{ item.price }}</p>
      <div class="swipper-info">
        <p class="swipper-property">
          Полотно коллекции
          <span class="swipper-property-ceiling">{{
            item.collectionCanvas
          }}</span>
        </p>
        <p class="swipper-property">
          Профиль
          <span class="swipper-property-ceiling">{{ item.profile }}</span>
        </p>
        <p class="swipper-property">
          Крепление под люстру
          <span class="swipper-property-ceiling">{{ item.fastening }}</span>
        </p>
        <p class="swipper-property">
          Выкройка углов
          <span class="swipper-property-ceiling">{{ item.angles }}</span>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'item-project',
  props: {
    items: {
      type: Array,
      required: true,
    },
  },
};
</script>

<style scoped>
.swipper {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  font-style: normal;
  font-family: Rubik;
  font-weight: 500;
  margin: 64px 0px 100px 0px;
  gap: 40px;
}
.swipper-item {
  max-width: 660px;
  max-height: 693px;
}
.swipper-image {
  width: 100%;
  height: 60%;
}
.swipper-name {
  color: #333;
  font-size: 26px;
  line-height: normal;
  margin-top: 32px;
}
.swipper-price {
  font-size: 32px;
  margin-top: 12px;
  line-height: normal;
  background: var(
    --main,
    linear-gradient(128deg, #615bd6 14.8%, #528fef 85.41%)
  );
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.swipper-info {
  font-family: Lato;
  line-height: 25px;
  color: #838383;
  font-size: 18px;
  font-weight: 400;
  margin-top: 16px;
}
.swipper-property-ceiling {
  color: #333;
}
</style>
