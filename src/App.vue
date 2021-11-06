<template>
  <div id="app">
       <main>
 
       <Header/>
       <Spirit />
       <Service />
       <About />
       <Portfolio/>
       <Blog/>
       <Contact/>
       <Footer/>

    
   
  
   </main>
  </div>
</template>

<script>
import Spirit from './components/Spirit.vue'
import Header from './components/Header.vue'
import Service from './components/Service.vue'
import About from './components/About.vue'
import Portfolio from './components/Portfolio.vue'
import Blog from './components/Blog.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
   components: {
     Header,
    Spirit,
    Service,
    About,
    Portfolio,
    Blog,
    Contact,
    Footer
  }
}
</script>

<style>

</style>
