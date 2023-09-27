<template>
  <div class="type">
    <h2 class="type-heading">Типы потолков</h2>
    <div class="type-checkbox">
      <input class="type-change" id="Matte" type="radio" name="typing"/><label
        class="type-checkbox-text"
        for="Matte"
        >Матовые</label
      >
      <input class="type-change" id="Satin" type="radio" name="typing"/><label
        class="type-checkbox-text"
        for="Satin"
        >Сатиновые</label
      >
      <input class="type-change" id="Glossy" type="radio" name="typing"/><label
        class="type-checkbox-text"
        for="Glossy"
        >Глянцевые</label
      >
      <input class="type-change" id="Multilevel" type="radio" name="typing"/><label
        class="type-checkbox-text"
        for="Multilevel"
        >Многоуровневые</label
      >
    </div>
    <information-type-ceiling />
  </div>
</template>

<script>
import InformationTypeCeiling from './TypeCeiling/InformationTypeCeiling';
export default {
  components: {
    InformationTypeCeiling,
  },
};
</script>

<style>
.type {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background: #f4f4f4;
  font-style: normal;
  width: 100%;
  height: 992px;
}
.type-heading {
  color: #333;
  font-family: Rubik;
  font-size: 44px;
  font-weight: 500;
  line-height: 44px;
  margin-top: 100px;
}
.type-checkbox {
  display: flex;
  align-items: center;
  gap: 48px;
  margin-top: 32px;
}
.type-checkbox label {
  display: inline-flex;
  padding: 12px 20px;
  align-items: flex-start;
  gap: 10px;
}
.type-checkbox-text {
  cursor: pointer;
  color: #333;
  font-family: Lato;
  font-size: 18px;
  font-weight: 400;
}
.type-checkbox input[type='radio'] {
  position: absolute;
  display: none;
}
.type-checkbox label:hover {
  border: 1px solid #908bef;
  border-radius: 100px;
}
.type-checkbox input[type='radio']:checked + label {
  display: inline-flex;
  align-items: flex-start;
  border-radius: 100px;
  border: 1px solid #615bd6;
}
</style>
