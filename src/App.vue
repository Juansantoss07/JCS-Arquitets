<script>

  import Header from "./components/Header.vue";
  import Home from "./components/Sections/Home.vue";
  import Projects from "./components/Sections/Projects.vue";
  import About from "./components/Sections/About.vue";
  import Contact from "./components/Sections/Contact.vue";
  import Footer from "./components/Footer.vue"

  export default{
    components:{
      Header,
      Home,
      Projects,
      About,
      Contact,
      Footer
    }
  }
</script>

<template>
  <Header/>
  <Home/>
  <Projects/>
  <About/>
  <Contact/>
  <Footer/>
</template>

<style>
  *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

      .title{
        padding: 1rem 0;
        font-size: 24px;
    }

    body::-webkit-scrollbar {
  width: 8px;    
}

body::-webkit-scrollbar-track {
  background: transparent;   
}

body::-webkit-scrollbar-thumb {
  background-color: #0D8AC0; 
}

</style>