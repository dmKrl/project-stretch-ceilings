<template>
  <div class="comments">
    <div class="comments-box">
      <heading-and-buttons>Отзывы наших клиентов</heading-and-buttons>
      <div class="comments-items">
        <comment-of-user :users="users" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      users: [
        {
          img: '../../../static/images/person1.svg',
          username: 'Заявка',
          text: 'Компания хорошая. Приветливые менеджеры. Большой выбор потолков на любой вкус. Монтажники работают качественно. Будет возможность ещё, закажем потолки в этой компании.',
        },
        {
          img: '../../../static/images/person1.svg',
          username: 'Выезд замерщика',
          text: 'В квартире потолки очень низкие, а это ведь урезать еще больше. Но и красить каждый раз потолок надоело. В итоге, установил везде глянец, помещение и правда смотрится больше и теперь никакой возни с потолками.',
        },
        {
          img: '../../../static/images/person1.svg',
          username: 'Монтаж',
          text: 'Наконец купила свою квартиру. Очень хотелось ее немного визуально расширить. Обратилась в вашу компанию, где мне рассказали про возможность установить разноцветный двухуровневый потолок. Нисколько не пожалела!',
        },
        {
          img: '../../../static/images/person1.svg',
          username: 'Приём работ',
          text: 'Наконец купила свою квартиру. Очень хотелось ее немного визуально расширить. Обратилась в вашу компанию, где мне рассказали про возможность установить разноцветный двухуровневый потолок. Нисколько не пожалела!',
        },
      ],
    };
  },
};
</script>

<style scoped>
.comments {
  display: flex;
  flex-direction: column;
  background: #f4f4f4;
}
.comments-box {
  margin: 100px auto;
}
.comments-items {
  display: flex;
  justify-content: center;
  gap: 40px;
}
</style>
