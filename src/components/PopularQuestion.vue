<template>
  <div class="questions">
    <h2 class="questions-heading">Популярные вопросы</h2>
    <div class="questions-box">
      <div>
        <ul>
          <li>
            В чем разница между матовыми, сатиновыми и глянцевыми потолками?
            <button>+</button>
          </li>
          <li>Какие светильники можно устанавливать на натяжные потолки?</li>
          <li>Что делать если порвался натяжной потолок?</li>
          <li>Можно ли устанавливать натяжной потолок в ванную комнату?</li>
          <li>Каким образом очищать натяжной потолок?</li>
        </ul>
      </div>
      <div class="questions-contact">
        <p>Не нашли ответ на вопрос?</p>
        <p>Позвоните нам</p>
        <p>+7 912-234-34-34</p>
        <p>Работаем круглосуточно</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
ul {
  list-style-type: none;
}
li {
  border-top: 1px solid white;
  border-bottom: 1px solid white;
  padding: 20px 0px;
  color: #fff;
  font-family: Rubik;
  font-size: 28px;
  font-style: normal;
  font-weight: 500;
  line-height: 36px;
}
.questions {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  padding: 100px 140px;
  background: linear-gradient(93deg, #5c55f4 4.53%, #7772eb 94.71%);
}
.questions-heading {
  color: #fff;
  font-family: Rubik;
  font-size: 52px;
  font-style: normal;
  font-weight: 500;
  line-height: 64px; /* 123.077% */
}
.questions-box {
  display: flex;
  padding-top: 64px;
}

.questions-contact {
  margin-left: 102px;
  background: #fff;
  padding: 50px 40px;
  max-height: 269px;
}
</style>
