<template>
   
    <section class="container mt-5 mb-5">
      <div class="contact">
        <div class="row g-2">
          <div class="title">
            <h5 class="mt-3 text-uppercase">Contact Us</h5>
            <h1 class="mt-3 mb-5">Get in Touch </h1>
        </div><br>
        
        <div class="col-md-6">
          <div class="mb-3">
            <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Your email">
          </div>
        </div>

        <div class="col-md-6">
          <div class="mb-3">
            <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Subject">
          </div>
        </div>
        <div class="col-md-12">
          <div class="mb-3">
            <textarea class="form-control" placeholder="Message here..." id="exampleFormControlTextarea1" rows="3"></textarea>
          </div>
        </div>
        <div class="see mt-4">
          <button class="btn btn-more " type="submit">Send Message</button>

        </div>

        </div>
      </div>
    </section>

     
</template>

<script>
export default {
  name: 'Contact',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
