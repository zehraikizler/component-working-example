<template>
  <div class="row">
    <!--logo-->
    <div class="col-sm-12">
        <a href="#">
            <img src="../../assets/moorninglogo.png" class="img-thumbnail" alt="logo">
        </a>
    </div>
    <div class="col-sm-12">
        <p class="mt-3 fs-5">There is no compromising real food, a real place, and fresh, authentic ingredients.</p>
    </div>
  </div>
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

a{
    text-decoration: none;
    color: #163A28;
    display: block;
}

a:hover{
    color: #163A28;
}
</style>