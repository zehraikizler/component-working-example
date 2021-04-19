<template>
  <div class="container-fluid underline my-3 pb-3">
    <div class="row">
      <!--navbar and text-->
      <div class="col-md-6 col-sm-12 d-flex">
         <NavbarAndText />           
      </div>
      <!--image-->
      <div class="col-md-6 p-5 p-lg-0 col-sm-auto">
        <HomeImage />
      </div>
    </div>
  </div>
</template>

<script>
import NavbarAndText from "./NavbarAndText";
import HomeImage from "./HomeImage";
export default {
  components: {
      NavbarAndText,
      HomeImage,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container-fluid{
    width: 100%;
}

.underline{
    border-bottom: solid 1px;
}
</style>
