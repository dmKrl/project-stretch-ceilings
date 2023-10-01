<template>
  <div class="app">
    <header-main />
    <first-frame />
    <type-ceiling />
    <advantages-ceilings />
    <application-screen />
    <how-to-order />
    <popular-question />
    <our-projects/>
    <vantage-work-us />
    <footer-main />
  </div>
</template>

<script>
import HeaderMain from './components/HeaderMain';
import FirstFrame from './components/FirstFrame';
import TypeCeiling from './components/TypeCeiling';
import FooterMain from './components/FooterMain';
import AdvantagesCeilings from './components/AdvantagesCeilings';
import ApplicationScreen from './components/ApplicationScreen';
import HowToOrder from './components/HowToOrder';
import PopularQuestion from './components/PopularQuestion';
import VantageWorkUs from './components/VantageWorkUs';
import OurProjects from './components/OurProjects';
export default {
  components: {
    HeaderMain,
    FirstFrame,
    TypeCeiling,
    FooterMain,
    AdvantagesCeilings,
    ApplicationScreen,
    HowToOrder,
    PopularQuestion,
    VantageWorkUs,
    OurProjects,
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
  background: none;
  cursor: pointer;
}

.app {
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}
</style>
