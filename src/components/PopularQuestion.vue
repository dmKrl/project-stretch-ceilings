<template>
  <div class="questions">
    <h2 class="questions-heading">Популярные вопросы</h2>
    <div class="questions-box">
      <div>
        <ul>
          <li v-for="question in questions">
            <div class="questions-main">
              <p>
                {{ question.text }}
              </p>
              <button-view></button-view>
            </div>
            <p class="questions-answer">{{ question.answer }}</p>
          </li>
        </ul>
      </div>
      <div class="questions-contact">
        <h4 class="questions-find">Не нашли ответ на вопрос?</h4>
        <p class="questions-call">Позвоните нам</p>
        <p class="questions-number">+7 912-234-34-34</p>
        <p class="questions-working">Работаем круглосуточно</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      questions: [
        {
          text: 'В чем разница между матовыми, сатиновыми и глянцевыми потолками?',
          answer:
            'Матовые натяжные потолки имитируют оштукатуренный потолок. Сатиновый натяжной потолок имеет перламутровый отблеск, что придает ему зеркальный эффект. Глянцевый натяжной потолок подходит для зрительного увеличения комнаты.',
        },
        {
          text: 'Какие светильники можно устанавливать на натяжные потолки?',
          answer:
            'Матовые натяжные потолки имитируют оштукатуренный потолок. Сатиновый натяжной потолок имеет перламутровый отблеск, что придает ему зеркальный эффект. Глянцевый натяжной потолок подходит для зрительного увеличения комнаты.',
        },
        {
          text: 'Что делать если порвался натяжной потолок?',
          answer:
            'Матовые натяжные потолки имитируют оштукатуренный потолок. Сатиновый натяжной потолок имеет перламутровый отблеск, что придает ему зеркальный эффект. Глянцевый натяжной потолок подходит для зрительного увеличения комнаты.',
        },
        {
          text: 'Можно ли устанавливать натяжной потолок в ванную комнату?',
          answer:
            'Матовые натяжные потолки имитируют оштукатуренный потолок. Сатиновый натяжной потолок имеет перламутровый отблеск, что придает ему зеркальный эффект. Глянцевый натяжной потолок подходит для зрительного увеличения комнаты.',
        },
        {
          text: 'Каким образом очищать натяжной потолок?',
          answer:
            'Матовые натяжные потолки имитируют оштукатуренный потолок. Сатиновый натяжной потолок имеет перламутровый отблеск, что придает ему зеркальный эффект. Глянцевый натяжной потолок подходит для зрительного увеличения комнаты.',
        },
      ],
    };
  },
};
</script>

<style scoped>
ul {
  list-style-type: none;
}
li {
  border-top: 1px solid white;
  border-bottom: 1px solid white;
  max-width: 760px;
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
  font-style: normal;
  padding: 100px 140px;
  background: linear-gradient(93deg, #5c55f4 4.53%, #7772eb 94.71%);
}
.questions-heading {
  color: #fff;
  font-family: Rubik;
  font-size: 52px;
  font-style: normal;
  font-weight: 500;
  line-height: 64px;
}
.questions-main {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.questions-box {
  display: flex;
  padding-top: 64px;
}
.questions-answer {
  display: none;
  color: rgba(255, 255, 255, 0.8);
  font-size: 18px;
  font-weight: 400;
  line-height: 26px;
}
.questions-contact {
  margin-left: 102px;
  background: #fff;
  padding: 50px 40px;
  max-height: 280px;
}
.questions-find {
  font-family: Rubik;
  max-width: 219px;
  font-size: 28px;
  font-weight: 500;
  line-height: 32px;
  background: var(
    --main,
    linear-gradient(128deg, #615bd6 14.8%, #528fef 85.41%)
  );
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.questions-call {
  color: #333;
  font-family: Lato;
  font-size: 18px;
  font-weight: 400;
  line-height: 18px;
  margin-top: 2rem;
}
.questions-number {
  color: #333;
  font-family: Rubik;
  font-size: 18px;
  font-weight: 600;
  margin-top: 12px;
}
.questions-working {
  color: #808080;
  font-family: Lato;
  font-size: 16px;
  font-weight: 400;
  line-height: 18px;
  margin-top: 4px;
}
</style>
