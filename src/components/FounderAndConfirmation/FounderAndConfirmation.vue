<template>
  <div class="container-fluid underline">
    <div class="row mx-0 mx-sm-5">
      <!--founding post-->
      <div class="col-md-8 col-sm-12 mt-5">
        <FoundingPost />
      </div>
      <!--founder's approval-->
      <div class="col-md-4 col-sm-12 justify-content-center justify-content-lg-start position-relative d-flex">
        <FoundersApproval />
      </div>
    </div>
   </div>
</template>

<script>
import FoundingPost from "./FoundingPost";
import FoundersApproval from "./FoundersApproval";
export default {
  components: {
    FoundingPost,
    FoundersApproval,
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
