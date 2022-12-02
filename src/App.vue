<script>
import theHeader from './components/theHeader.vue';
import theFooter from "./components/theFooter.vue";
import firstBanner from "./components/firstBanner.vue";
import secondBanner from "./components/secondBanner.vue";
export default {
  components: { theHeader, theFooter, firstBanner, secondBanner }
};
</script>
<template>
  <theHeader></theHeader>
  <main class="bg-black" style="height: 150px;">
    <div class="container mt-3 pb-5">
      <h2 class="pt-5 text-white"> -- Content goes here -- </h2>
    </div>
    <firstBanner></firstBanner>
    <theFooter></theFooter>
    <secondBanner></secondBanner>
  </main>
</template>


<style scoped>

</style>