<template>
   <section class="container mt-5 ">
      <div class="check">
       <div class="row">
        <div class="title">
          <h5 class="mt-3 text-uppercase">blog stories</h5>
          <h1 class="mt-3 mb-5">Check Our News          
             <span class="float-end" ><i class="left fal fa-arrow-left"></i> <i class="fal fa-arrow-right"></i></span>
          </h1>
      </div><br>
      
      <div class="col-md-4">
        <div class="top card shadow-sm p-3 mb-5 bg-body rounded" >
          <div class="card-body">
            <h4 class="card-title mb-3 ">New Adventure</h4>
            <h5 class="card-title ">15 March 2019</h5>
            <p class="card-text mt-5 mb-3 text-muted">Some quick example text to build on the card title and make 
              up the bulk of the card's content  title and make 
              up the bulk of the card's content.</p>
              <span class="float-end mt-3" ><i class="fal fa-arrow-right"></i></span>

          </div>
        </div>
      </div>

      <div class="col-md-4 "  v-for="index in 2" :key="index">
        <div class="sec card shadow-sm p-3 mb-5 bg-body rounded" >
          <div class="card-body">
            <h4 class=" sec card-title mb-3">New Adventure</h4>
            <h5 class="card-title ">15 March 2019</h5>
            <p class="card-text mt-5 mb-3">Some quick example text to build on the card title and make 
              up the bulk of the card's content  title and make 
              up the bulk of the card's content.</p>
              <span class="float-end mt-3" ><i class="fal fa-arrow-right"></i></span>

          </div>
        </div>
      </div>
    

       </div>
      </div>
    </section>

     
</template>

<script>
export default {
  name: 'Bolg',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
