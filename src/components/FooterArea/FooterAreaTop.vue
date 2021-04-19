<template>
  <span>
    <p class="text-center my-5 fs-4">Morning is open for dinner every day from 5pm-midnight.</p>
    <div class="button2hover position-relative d-flex  justify-content-center">
        <div class="buttonborderline"> 
          <button type="button" class="btn position-relative rounded-0 d-flex">Book a table <img src="../../assets/buttonarrow.png" class="img-thumbnail arrowcolor d-flex" alt="arrow"></button>
        </div>
    </div>  
    <img src="../../assets/footerimage.png" class="img-thumbnail px-2 pt-5 mt-5" alt="footerimage">
  </span>
</template>

<script>
export default {
  name: "HelloWorld",
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.img-thumbnail{
    background-color: #EDECEA; 
    border: 0;
}

.button2hover{
    z-index: 99999;
}

.button2hover:hover{
    cursor: pointer;
}

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
</style>