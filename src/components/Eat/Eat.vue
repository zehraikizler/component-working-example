<template>
   <div class="container-fluid underline my-3">
    <div class="row mt-5 py-5">
      <!--eat and image-->
      <div class="col-md-4 col-sm-12 d-flex">
        <EatAndImage />
      </div>
      <!--diet list-->
      <div class="col-md-8 col-sm-12">  
        <EatDietList />
      </div>
    </div>
   </div>
</template>

<script>
import EatAndImage from "./EatAndImage";
import EatDietList from "./EatDietList";
export default {
  components: {
      EatAndImage,
      EatDietList,
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