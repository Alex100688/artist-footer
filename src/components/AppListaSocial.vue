<script>
export default {
  name: "AppListaSocial",
};
</script>
<template>
  <section class="container">
    <div class="row">
      <div class="col-3 my-3">
        <i class="fa-brands fa-facebook fb"></i>
        <i class="fa-brands fa-instagram ig"></i>
        <i class="fa-brands fa-youtube yt"></i>
        <i class="fa-brands fa-linkedin ld"></i>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.fb,
.ig,
.ld,
.yt {
  margin-top: 0.625rem;
  margin-bottom: 0.625rem;
  margin-left: 0.1875rem;
  font-size: 1.875rem;
}
.ig,
.yt,
.ld {
  color: white;
}
.fb {
  color: #00418e;
}

.yt {
  background-color: red;
}
</style>
