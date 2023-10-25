<template>
  <div class="app">
    <header-main />
    <first-frame />
    <type-ceiling />
    <advantages-ceilings />
    <application-screen />
    <how-to-order />
    <popular-question />
    <our-projects />
    <vantage-work-us />
    <footer-main />
  </div>
</template>

<script>
import HeaderMain from './components/page/HeaderMain/HeaderMain';
import FirstFrame from './components/page/FirstFrame/FirstFrame';
import TypeCeiling from './components/page/TypeCeiling/TypeCeiling';
import FooterMain from './components/page/FooterMain/FooterMain';
import AdvantagesCeilings from './components/page/AdvantagesCeilings/AdvantagesCeilings';
import ApplicationScreen from './components/page/ApplicationScreen/ApplicationScreen';
import HowToOrder from './components/page/HowToOrder/HowToOrder';
import PopularQuestion from './components/page/PopularQuestion/PopularQuestion';
import VantageWorkUs from './components/page/VantageWorkUs/VantageWorkUs';
import OurProjects from './components/page/OurProject/OurProjects';
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
