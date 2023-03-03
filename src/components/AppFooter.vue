<script>
import AppFooterTop from "./AppFooterTop.vue";
import AppFooterBottom from "./AppFooterBottom.vue";
export default {
  name: "AppFooter",
  components: {
    AppFooterTop,
    AppFooterBottom,
  },
};
</script>
<template>
  <div class="container text-center">
    <!-- dove c'è scritto Logo ci vuole il logo -->
    <img class="img-fluid mb-5" src="../assets/logowhite.png" alt="" />
    <AppFooterTop />
    <AppFooterBottom class="mt-5" />
  </div>
</template>

<style lang="scss" scoped>
h3,
p {
  color: white;
}
</style>
