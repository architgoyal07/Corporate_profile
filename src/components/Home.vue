<template>
  <div class="home" >
    
    <div class="image">
      <img src="../assets/archit2.jpg" width="30%" height="auto" >
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
</template>

<script>
export default {
  name: "HelloWorld",

};
</script>


<style scoped lang="scss">

 

  .home{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  h1{
    font-size: 5vw;
    font-family: sans-serif;
  }

  h4{
    color: lightgray;
    font-size: 2vw;
  }
  .links{
    font-size: 2vw;
  }

  a{
    color: lightslategray;
  }
  a:hover{
    color: white;
  }
</style>
