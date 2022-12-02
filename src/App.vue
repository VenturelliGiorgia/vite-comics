<script>
import theHeader from './components/theHeader.vue';
import theFooter from "./components/theFooter.vue";
import firstBanner from "./components/firstBanner.vue";
export default {
  components: { theHeader, theFooter, firstBanner}
};
</script>
<template>
  <theHeader></theHeader>
  <main class="bg-black" style="height: 150px;">
    <div class="container mt-3 pb-5">
      <h2 class="pt-5 text-white"> -- Content goes here -- </h2>
    </div>
    <firstBanner></firstBanner>
  </main>
</template>


<style scoped>

</style>