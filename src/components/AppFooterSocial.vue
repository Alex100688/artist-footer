<script>
import AppListaSocial from "./AppListaSocial.vue";
import AppFooterDomande from "./AppFooterDomande.vue";
import AppFooterRisposte from "./AppFooterRisposte.vue";
export default {
  name: "AppFooterSocial",
  components: {
    AppListaSocial,
    AppFooterDomande,
    AppFooterRisposte,
  },
};
</script>
<template>
  <section class="container">
    <div class="row">
      <div class="col">
        <h5>I nostri canali social:</h5>
        <AppListaSocial class="" />
      </div>
      <div class="col">
        <h5>Le vostre domande frequenti:</h5>
        <AppFooterDomande />
      </div>
      <div class="col">
        <h5>Le migliori risposte:</h5>
        <AppFooterRisposte />
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
h5 {
  color: white;
}
</style>
