<template>
  <button class="button-price"><slot></slot></button>
</template>

<script>
export default {
  name: 'button-price',
};
</script>

<style scoped>
.button-price {
  display: inline-flex;
  align-items: flex-start;
  padding: 20px 32px;
  margin-top: 3rem;
  gap: 10px;
  border-radius: 100px;
  background: var(
    --main,
    linear-gradient(128deg, #615bd6 14.8%, #528fef 85.41%)
  );
  color: #fff;
  font-family: Lato;
  font-size: 1rem;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  transition: all 0.8s;
}
.button-price:hover {
  background: var(
    --main,
    linear-gradient(128deg, #7a75e8 14.8%, #528fef 85.41%)
  );
  transform: scale(1.01);
}
</style>
