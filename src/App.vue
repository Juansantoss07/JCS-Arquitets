<script>

  import Header from "./components/Header.vue";
  import Home from "./components/Sections/Home.vue"
  export default{
    components:{
      Header,
      Home
    }
  }
</script>

<template>
  <Header/>
  <Home/>
</template>

<style>
  *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

</style>