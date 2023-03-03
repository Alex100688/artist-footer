<script>
export default {
  name: "AppListaSocial",
};
</script>
<template>
  <section class="container">
    <a href=""><i class="fa-brands fa-facebook fb"></i></a>
    <a href=""><i class="fa-brands fa-instagram ig"></i></a>
    <a href=""><i class="fa-brands fa-youtube yt"></i></a>
    <a href=""><i class="fa-brands fa-linkedin ld"></i></a>
  </section>
</template>
<style lang="scss" scoped>
a {
  text-decoration: none;
}
.fb,
.ig,
.ld,
.yt {
  margin-top: 0.625rem;
  margin-left: 0.625rem;
  padding-right: 0.3125rem;
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
