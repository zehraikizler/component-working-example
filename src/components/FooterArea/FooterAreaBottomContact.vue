<template>
  <div class="row">
    <!--page links-->
    <div class="col-6">
        <a href="#" class="mb-1 me-5">home</a>
        <a href="#" class="mb-1 me-5">eat</a>
        <a href="#" class="mb-1 me-5">drink</a>
        <a href="#" class=" me-5">bookings</a>
    </div>
    <!--contact-->
    <div class="col-6">
        <a href="https://www.instagram.com/?hl=tr" target="_blank" class="mb-1">instagram</a>
        <a href="https://tr-tr.facebook.com/" target="_blank" class="mb-1">facebook</a>
        <a href="#" class="mb-1">contact</a>
        <a href="#" class="link">we're hiring</a>
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
a{
    text-decoration: none;
    color: #163A28;
    display: block;
}

a:hover{
    color: #163A28;
}

.link{
    width: 80px;
}
</style>