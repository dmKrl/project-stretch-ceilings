<template>
  <div class="calculate">
    <h2 class="calculate-heading">
      Поможем расчитать стоимость и подобрать материалы
    </h2>
    <div>
      <information-about-ceiling stylesText="custom custom-block" stylesBlock="custom-block"/>
    </div>
    <button-price style="margin-top: 0px; color: black; background: white"
      >Расчитать стоимость</button-price
    >
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.calculate {
  display: flex;
  color: white;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 100px 0px;
  background: linear-gradient(93deg, #5c55f4 4.53%, #7772eb 94.71%);
  gap: 48px;
}

</style>
