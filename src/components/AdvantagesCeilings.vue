<template>
  <div class="advantages">
    <h2 class="advantages-heading">
      <price-ceiling>Преимущества</price-ceiling> натяжных потолков
    </h2>
    <div class="advantages-box">
      <div class="advatages-box-up">
        <advantage-ceiling />
        <advantage-ceiling />
      </div>
      <div class="advatages-box-down">
        <advantage-ceiling />
        <advantage-ceiling />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.advantages {
  display: flex;
  justify-content: center;
  align-items: center;
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
