<template>
   
  
           <section class="container mt-5 ">
      <div class="port">
       
       <div class="row g-4">
        <div class="title">
          <h1 class="mt-3">See some of our</h1>
          <h1>Creative Work.          
             <span class="float-end" ><i class="left fal fa-arrow-left"></i> <i class="fal fa-arrow-right"></i></span>
          </h1>
         </div>
        <div class="col-md-4" v-for="index in 6" :key="index">
          <img src="../assets/images/abstract-surface-textures-white-concrete-stone-wall_74190-8184.jpg" class="h-100 w-100" alt="...">
        </div>
        <div class="see">
          <button class="btn btn-get " type="submit">See More Of These. </button>

        </div>
       </div>
      </div>
    </section>
     
</template>

<script>
export default {
  name: 'Portfolio',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
