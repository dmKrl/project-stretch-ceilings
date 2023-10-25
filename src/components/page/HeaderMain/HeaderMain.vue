<template>
  <div class="header">
    <my-logo />
    <nav class="header-nav">
      <a class="header-link" href="#">О нас</a>
      <a class="header-link" href="#">Как заказать</a>
      <a class="header-link" href="#">Вопросы и ответы</a>
      <a class="header-link" href="#">Проекты</a>
      <a class="header-link" href="#">Отзывы</a>
    </nav>
    <contact />
  </div>
</template>

<script>
export default {};
</script>

<style>
.header {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  margin: 20px 0px;
}
.header-nav {
  display: flex;
  gap: 2rem;
}
.header-link {
  color: #333;
  font-family: Lato;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.header-link:hover {
  color: #615bd6;
}
</style>
