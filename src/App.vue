<template>
  <div>
    <the-title-vue></the-title-vue>
    <base-spinner-css></base-spinner-css>
    <clock-loader-css></clock-loader-css>
    <pulse-loader-css></pulse-loader-css>
    <glass-loader-css></glass-loader-css>
    <round-smooth-loader></round-smooth-loader>
  </div>
</template>

<script>
import GlassLoaderCss from './components/GlassLoaderCSS.vue';
import TheTitleVue from './components/TheTitle.vue';
import BaseSpinnerCss from './components/BaseSpinnerCSS.vue';
import ClockLoaderCss from './components/ClockLoaderCSS.vue';
import RoundSmoothLoader from './components/RoundSmoothLoader.vue';
//  glass loader css not yet imported

import PulseLoaderCss from './components/PulseLoaderCSS.vue';
export default {
  components: {
    TheTitleVue,
    BaseSpinnerCss,
    ClockLoaderCss,
    PulseLoaderCss,
    GlassLoaderCss,
    RoundSmoothLoader,
  },
};
</script>

<style scoped>
div {
  background: blue;
}
</style>
