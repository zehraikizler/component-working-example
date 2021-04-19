<template>
  <div class="container-fluid underline my-3">
    <div class="row mt-5 py-5">
      <!--drink and image-->
      <div class="col-md-4 col-sm-12 d-flex">
        <DrinkAndImage />
      </div>
      <!--diet list-->
      <div class="col-md-8 col-sm-12">         
        <DrinkDietList />        
      </div>
    </div>
   </div>
</template>

<script>
import DrinkAndImage from "./DrinkAndImage";
import DrinkDietList from "./DrinkDietList";
export default {
  components: {
      DrinkAndImage,
      DrinkDietList,
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