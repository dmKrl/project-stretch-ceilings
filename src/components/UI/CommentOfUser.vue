<template>
  <div v-for="user in users" class="client">
    <img :src="user.img" alt="" />
    <p class="user-name">{{ user.username }}</p>
    <p class="user-quote">❞</p>
    <p class="user-info">{{ user.text }}</p>
  </div>
</template>

<script>
export default {
  name: 'comment-of-user',
  props: {
    users: {
      type: Array,
      required: true,
    },
  },
};
</script>

<style scoped>
img {
  display: inline-block;
}
.client {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 24px;
  padding: 48px 24px;
  max-width: 360px;
  max-height: 526px;
}
.user-name {
  color: var(--, #333);
  font-family: Rubik;
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.user-quote {
  font-family: Rubik;
  font-size: 56px;
  font-style: normal;
  font-weight: 500;
  line-height: 48px;
}
.user-info {
  color: rgba(0, 0, 0, 0.8);
  text-align: center;
  font-family: Lato;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 24px;
}
</style>
