<template>
  <div class="mt-2 mb-5 me-5 fs-3 ">
    <p class="mb-5 pb-4">Contemporary plant-based Mexican restaurant in the heart of Melbourne. At Morning, we cook to enhance the taste of corn, chiles and Mexican spices in a variety of dishes that are part of our cultural identity with a twist to adapt and reach out to the Australian culture.</p>
    <!--bookins button-->
    <div class="row buttonhover d-flex justify-content-center justify-content-lg-start">
        <div class="col-5">
            <div class="buttonborderline">
                <button type="button" class="btn position-relative rounded-0">Book a table <img src="../../../assets/buttonarrow.png" class="img-thumbnail arrowcolor" alt="arrow"></button>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.buttonborderline{
    border: #163A28 solid 1px; 
    position: absolute; 
    z-index: -11111;
}

.btn{
    background-color: #163A28; 
    color: white !important; 
    top: -7px; 
    left: -7px;
}

.arrowcolor{
    background-color: #163A28;
    border: 0px;
}

.buttonhover{
    height: 50px;
    width: 200px;
}

.buttonhover:hover{
    cursor: pointer;
}
</style>
