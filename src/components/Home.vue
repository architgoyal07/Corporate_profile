<template>
  
  <div class="outer">
  
    <div class="home" >
    
  
    <div class="image">
      <img src="../assets/archit2.jpg" style="width:80%;max-width:400px;">
    </div>

    <div class="title">
      <h1>Archit Goyal</h1>
      <br>
      <h4>FrontEnd Developer</h4>
    </div>
     <br>

    <div class="links">
        
         <a href="https://www.linkedin.com/in/archit-goyal-8a6957133/"><span class="mdi mdi-linkedin"></span></a>
         <a href="https://app.slack.com/client/TDGG421C1/DR80DRPJA/user_profile/WLLJMQLPL"><span class="mdi mdi-slack"></span></a>
         <a href="https://github.com/architgoyal07"><span class="mdi mdi-github-circle"></span></a>
         <a href="https://twitter.com/i_Am_archit"> <span class="mdi mdi-twitter"></span></a>
         <a href="https://www.facebook.com/archit.goyal.77"> <span class="mdi mdi-facebook"></span></a>
         <a href="https://www.instagram.com/_archit_goyal/"> <span class="mdi mdi-instagram"></span></a>
          
    </div>

   </div>
  </div>
</template>

<script>
export default {
  

};
</script>


<style scoped lang="scss">

  .outer{
    display: table;
    width: 100%;
    height: 100vh;
  }

  .home{
    display: table-cell;
    vertical-align: middle;
    text-align: center;
    flex-direction: column;
    overflow: auto;
  }

  div a{
    padding: 5px;
  }


  h1{
    font-size: 57px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  h4{
    color: lightgray;
    font-size: 35px;
  }
  .links{
    font-size: 30px;
  }

  a{
    color: lightslategray;
  }
    
  a:hover{
    color: white;
  }

  
</style>
