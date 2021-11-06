<template>
  
     <section class="container mt-5">
       <div class="web">
         <div class="row">
          <div class="col-md-4">
            <h1 class="mt-3">Anythings you</h1>
            <h1>need, we've.</h1>
            <h1 class="mb-4">get to covered.</h1>
              <button class="btn btn-more " type="submit">Get in Touch.</button>
          </div>

          <div class="col-md-4">
            <div class="card shadow-sm p-3 mb-5 bg-body rounded" >
              <img src="../assets/images/external-graphic-design-ux-and-ui-flatart-icons-outline-flatarticons.png" class="card-img-top w-20" alt="...">
              <div class="card-body">
                <h5 class="card-title">Web & Graphic</h5>
                <h5 class="card-title">Design</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="card shadow-sm p-3 mb-5 bg-body rounded" >
              <img src="../assets/images/edit-chat.png" class="card-img-top w-20" alt="...">
              <div class="card-body">
                <h5 class="card-title">Web & App</h5>
                <h5 class="card-title">Developement</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>

         </div>
       </div>
     </section>

     
</template>

<script>
export default {
  name: 'Service',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
