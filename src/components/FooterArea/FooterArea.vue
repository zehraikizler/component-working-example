<template>
  <div class="container-fluid my-3">
    <div class="mb-5 py-5">
      <FooterAreaTop />
    </div>
    <div class="row mx-5 pb-3 justify-content-between">
      <div class="col-md-4">
        <FooterAreaBottomMorning />       
      </div>
      <div class="col-md-4 mt-3">
        <FooterAreaBottomContact />      
      </div>
    </div>
   </div>
</template>

<script>
import FooterAreaTop from "./FooterAreaTop";
import FooterAreaBottomMorning from "./FooterAreaBottomMorning";
import FooterAreaBottomContact from "./FooterAreaBottomContact";
export default {
  components: {
     FooterAreaTop,
     FooterAreaBottomMorning,
     FooterAreaBottomContact,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container-fluid{
    width: 100%;
}

</style>