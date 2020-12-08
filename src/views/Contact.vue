<template>
    <div class="container mt-n6 home-body">
      <div class="home pa-2"> 
        <div class="gif-image">
            <img src="../assets/connect.gif" class="infinite"/>
        </div> 
        <div class="divider-heading my-4">
            <h3 class="divider">Let's connect !</h3>
        </div>
        <div class="contact-buttons d-none d-sm-flex">
           <span class="mx-14 hvr-grow"><a href="https://www.linkedin.com/in/akhil-kumar-92b37a128" target="_blank"><img src="../assets/linkedin.svg" alt="" height="50" width="50"></a></span>
           <span class="mx-14 hvr-grow"><a href="https://github.com/Akhilkmr78" target="_blank"><img src="../assets/GitHub-Mark-120px-plus.png"  height="50" width="50"></a></span>
           <span class="mx-14 hvr-grow"><a href="mailto:16m602@nith.ac.in"><img src="../assets/mail.svg" height="50" width="50"></a></span> 
           <span class="mx-14 hvr-grow"><a href="tel:+91 9971337754"><img src="../assets/call.svg" height="50" width="50"></a></span> 
        </div>
        <div class="contact-buttons d-flex d-sm-none">
           <span class="mx-4 hvr-grow"><a href="https://www.linkedin.com/in/akhil-kumar-92b37a128" target="_blank"><img src="../assets/linkedin.svg" alt="" height="25" width="25"></a></span>
           <span class="mx-4 hvr-grow"><a href="https://github.com/Akhilkmr78" target="_blank"><img src="../assets/GitHub-Mark-120px-plus.png"  height="25" width="25"></a></span>
           <span class="mx-4 hvr-grow"><a href="mailto:16m602@nith.ac.in"><img src="../assets/mail.svg" height="25" width="25"></a></span> 
           <span class="mx-4 hvr-grow"><a href="tel:+91 9971337754"><img src="../assets/call.svg" height="25" width="25"></a></span> 
        </div>   
      </div>  
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=PT+Mono&display=swap');

 /* .home-body{
    background-color:  rgba(233, 223, 223, 0.158);
  } */
  .home{
    width: 100%;
    height: fit-content;
    background-color: white;
  }
  .gif-image{
      display: flex;
      flex-direction: row;
      justify-content: center;
  }
  .contact-buttons{
      display: flex;
      flex-direction: row;
      justify-content: center;
      
  }
  .divider{
    font-family: 'PT Mono', monospace;
    font-weight: 600;
    
  }
  .divider-heading{
      display: flex;
      flex-direction: row;
      justify-content: center;
  }
  .infinite{
      width: 50%;
  }

  @media(max-width:1200px){
    .infinite{
      width: 70%;
  }
}
@media(max-width:600px){
  .infinite{
    width: 100%;
  }
}
  
</style>