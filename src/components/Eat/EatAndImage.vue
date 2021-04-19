<template>
  <div class="row">
    <div class="col-md-12 col-sm-6 position-relative">
        <h2 class="eat-drink ps-5 position-absolute">eat</h2>
        <img src="../../assets/backgroundvector.png" class="img-thumbnail" alt="background-vector">        
        <p class="eat-drinktext ps-5">Our menu is 100% vegan and prepared fresh daily.</p>
    </div>
    <div class="col-md-12 col-sm-6 mb-4 d-flex align-items-end">
        <img src="../../assets/eatimage.png" class="img-thumbnail" alt="eating">
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
.eat-drink{
    font-size: 70px;
}

.eat-drinktext{
    font-size: 17px;
    width: 250px; 
    color: black;
}

.img-thumbnail{
    background-color: #EDECEA; 
    border: 0;
}
</style>