<template>
  <div class="contact">
    <p class="contact-phone">8 912 234-34-34</p>
    <p class="contact-info">Работаем круглосуточно</p>
  </div>
</template>

<script>
export default {
  name: 'contact',
};
</script>

<style>
.contact {
  display: flex;
  flex-direction: column;
  text-align: end;
  text-align: right;
  font-family: Lato;
  font-style: normal;
  line-height: normal;
  font-size: 1rem;
}
.contact-phone {
  color: var(--, #333);
  font-weight: 600;
}
.contact-info {
  color: #808080;
  font-weight: 500;
}
</style>
