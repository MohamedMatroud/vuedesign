<template>
  
    <header class="container">
    <nav class="navbar navbar-expand-lg   mt-4">
      <div class="container-fluid">
          <a class="navbar-brand " href="#">Doob</a>
               
        <button class="navbar-toggler  navbar-light bg-light" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2  mb-lg-0">
            <li class="nav-item ">
              <a class="nav-link active" aria-current="page" href="#">Home.</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">About Us.</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Portfolio.</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Blog.</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact Us</a>
            </li>
          
            
           
          </ul>
          <ul class="navbar-nav">
            <li class="nav-item dropdown me-2">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                EN
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
              
              </ul>
            </li>
          </ul>
          <form class="d-flex">
           
            <!-- <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search"> -->
            <button class="btn btn-success shadow-sm p-3  bg-body rounded " type="submit">Contact Us <i class="fal fa-arrow-right"></i></button>
          </form>
        </div>
      </div>
    </nav>
   </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
