<template>
  <span class="justify-content-center justify-content-lg-start position-relative d-flex">
    <img src="../../assets/imzavector.png" class="img-thumbnail confirmationimage position-absolute bottom-0" alt="imza logo">
    <div class="d-flex mb-5 fs-5 align-items-end">
        <p class="me-2"><b>Josie Garcia</b></p>
        <p>Head Chef</p>
    </div>
  </span>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.img-thumbnail{
    background-color: #EDECEA; 
    border: 0;
}

.confirmationimage{
    z-index: -99999; 
    height: 150px; 
    width: 282px;
}
</style>