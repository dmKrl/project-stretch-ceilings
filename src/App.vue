<template>
  <div class="app">
    <header-main />
    <first-frame />
    <type-ceiling />
  </div>
</template>

<script>
import HeaderMain from './components/HeaderMain';
import FirstFrame from './components/FirstFrame';
import TypeCeiling from './components/TypeCeiling';
export default {
  components: {
    HeaderMain,
    FirstFrame,
    TypeCeiling,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

a {
  text-decoration: none;
}

button {
  border: none;
  cursor: pointer;
}

.app {
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}
</style>
