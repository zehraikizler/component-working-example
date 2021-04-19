<template>
  <div class="row">

    <!--navbar-->
    <div class="col-12">            
      <nav class="navbar navbar-expand-md navbar-light">
        <div class="container-fluid">
          <!--logo-->
            <a class="navbar-brand">
              <img src="../../assets/moorninglogo.png" class="img-fluid" alt="morning image">
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <!--content-->
              <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item me-2">
                  <a class="nav-link" href="#eat">eat</a>
                </li>
                <li class="nav-item me-2">
                  <a class="nav-link" href="#drink">drink</a>
                </li>
                <li class="nav-item me-2">
                  <a class="nav-link" href="#bookings">bookings</a>
                </li>
                <li class="nav-item me-2">
                  <a class="nav-link" href="#contacts">contacts</a>
                </li>
              </ul>                    
            </div>
        </div>
      </nav>
    </div>

    <!--text-->
    <div class="col-12 d-flex align-items-end">
      <div class="row mx-3 mx-xl-5 px-xl-4">
        <div class="col-12 fs-1 mb-2">
          <span class="headtext"> There is no compromising real food, a real place, and fresh,
            <div class="headtextbackground position-relative">
              <p>authentic</p>
              <img src="../../assets/backgroundvector.png" class="headtextbackgroundimage img-thumbnail position-absolute" alt="background vector">
            </div>  
            ingredients.
          </span>
        </div>
        <div class="col-12">
          <p>A celebration of México with Josie Garcia.</p>
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
.container-fluid{
    width: 100%;
}

.img-fluid{
    min-height: 30px !important;
    min-width: 128px !important;
}

.img-thumbnail{
    background-color: #EDECEA; 
    border: 0;
}

.headtext{
    display: inline;
}

.headtextbackground{
    display: inline-block;
}

.headtextbackgroundimage{
    z-index: -9999; 
    bottom: 0; 
    height: 100px;
    width: 300px;
}
</style>
