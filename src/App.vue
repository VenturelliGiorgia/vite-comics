<script>
import theHeader from './components/theHeader.vue';
import theFooter from "./components/theFooter.vue";
import firstBanner from "./components/firstBanner.vue";
import secondBanner from "./components/secondBanner.vue";
import mainContent from "./components/main.vue";
export default {
  components: { theHeader, theFooter, firstBanner, secondBanner, mainContent }
};
</script>
<template>
  <theHeader></theHeader>
  <main>
    <mainContent></mainContent>
    <firstBanner></firstBanner>
  </main>
  <theFooter></theFooter>
  <secondBanner></secondBanner>
</template>


<style lang="scss">
@use "./styles/general.scss";
</style>