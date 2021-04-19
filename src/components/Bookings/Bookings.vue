<template>
  <div class="container-fluid underline my-3">
    <div class="row my-5 py-5">
      <!--bookings image-->
      <div class="col-lg-6 col-12 d-flex justify-content-center">
       <BookingsContentImage />
      </div>
      <!--bookings text-->
      <div class="col-lg-6 col-12 ">
        <BookingsContent />
      </div>
    </div>
    <!--images-->
    <div>
      <BookingsImages />
    </div>
   </div>
</template>

<script>
import BookingsContent from "./BookingsContent/BookingsContent";
import BookingsContentImage from "./BookingsContent/BookingsContentImage";
import BookingsImages from "./BookingsImages";
export default {
  components: {
      BookingsContent,
      BookingsContentImage,
      BookingsImages,
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
