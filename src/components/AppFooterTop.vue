<script>
import AppFooterInformazioni from "./AppFooterInformazioni.vue";
import AppFooterContatti from "./AppFooterContatti.vue";
import AppFooterPartnerShip from "./AppFooterPartnerShip.vue";
import AppFooterPrivacy from "./AppFooterPrivacy.vue";
export default {
  name: "AppFooterTop",
  components: {
    AppFooterInformazioni,
    AppFooterContatti,
    AppFooterPartnerShip,
    AppFooterPrivacy,
  },
};
</script>
<template>
  <section class="container">
    <div class="row">
      <div class="col-4">
        <h6>Su di noi</h6>
        <AppFooterInformazioni />
      </div>
      <div class="col-4">
        <h6 class="ms-5">Contattaci</h6>
        <AppFooterContatti class="ms-3" />
      </div>
      <div class="col-4">
        <h6 class="ms-5">Privacy e Sicurezza</h6>
        <AppFooterPrivacy class="ms-3" />
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
h6 {
  color: #00418e;
  font-weight: bold;
}
</style>
