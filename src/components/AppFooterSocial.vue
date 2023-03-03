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
      <div class="col-4">
        <h6>I nostri canali social:</h6>
        <AppListaSocial />
      </div>
      <div class="col-4">
        <h6 class="ms-5">Le vostre domande frequenti:</h6>
        <AppFooterDomande class="ms-3" />
      </div>
      <div class="col-4">
        <h6 class="ms-5">Le migliori risposte:</h6>
        <AppFooterRisposte class="ms-3" />
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
h6 {
  color: #00418e;
}
</style>
