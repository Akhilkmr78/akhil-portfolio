<template>
  <div class="container mt-n6 home-body">
    <div class="home">
     <v-container>
       <div class="headline">
         <h5 class="text-center">Akhil Kumar</h5>
         <h6 class="text-center">Front-End Developer</h6>
         <div class="skills-badges text-center my-4">
           <span class="mx-6 hvr-grow"><img src="../assets/HTML5.svg" alt="" height="36" width="36"></span>
           <span class="mx-6  hvr-grow"><img src="../assets/Vue.svg" alt="" height="36" width="36"></span>
           <span class="mx-6  hvr-grow"><img src="../assets/CSS3.svg" alt="" height="38" width="38"></span>
           <span class="mx-6  hvr-grow"><img src="../assets/Materialize.svg" alt="" height="36" width="36"></span>
           <span class="mx-6  hvr-grow"><img src="../assets/Javascript.svg" alt="" height="36" width="36"></span>
           <span class="mx-6  hvr-grow"><img src="../assets/Vuetify.svg" alt="" height="36" width="36"></span>
           <span class="mx-6  hvr-grow"><img src="../assets/Sass.svg" alt="" height="36" width="36"></span>
           <span class="mx-6  hvr-grow"><img src="../assets/Firebase.svg" alt="" height="36" width="36"></span>
           <span class="mx-6  hvr-grow"><img src="../assets/git-icon.svg" alt="" height="36" width="36"></span>
         </div>
       </div>
             
            <div class="profile-paragraph container">
              <div class="profile-photo pt-3">
                <v-img 
                src="../assets/Akhil.jpg"  
                max-height="460" 
                max-width="340"
                min-height="320"
                min-width="210"
                
                ></v-img>
              </div>
              <div class="bio ml-4 text-justify d-none d-sm-flex">
                <h4>Hi, I'm <strong>Akhil</strong> ! creative front-end developer. 
                <br> 
                <br>
                Well versed in basic and advanced Front-end technologies such as Javascript, Vue.js , CSS and many more to thread alluring UI designs and layouts into fully functional, cross-device responsive websites and webapps.
                <br>
                <br>
                Currently located in Gurgaon, India; I'm actively looking for developer positions and willing to join dynamic, innovative, and collaborative team to showcase my web-development skills.
                <br>
                <br>
                For the past two years I was leading Research & Development Department in a Laser-Machine Development firm situated - Gurgaon, India. I decided career-shift in Front-end and UI development and still going strong improving prowess.
                <br>
                <br>
                I completed my Masters of Engineering in Mechanical Engineering from N.I.T. Hamirpur(H.P.) in 2018 and taught my-self Front-end development in summer 2020 with Javascript as my second programming language.
                </h4>
              </div>
              <div class="bio text-justify d-flex d-sm-none mt-4">
                <h4>Hi, I'm <strong>Akhil</strong> ! creative front-end developer. 
                <br> 
                <br>
                Well versed in basic and advanced Front-end technologies such as Javascript, Vue.js , CSS and many more to thread alluring UI designs and layouts into fully functional, cross-device responsive websites and webapps.
                <br>
                <br>
                Currently located in Gurgaon, India; I'm actively looking for developer positions and willing to join dynamic, innovative, and collaborative team to showcase my web-development skills.
                <br>
                <br>
                For the past two years I was leading Research & Development Department in a Laser-Machine Development firm situated - Gurgaon, India. I decided career-shift in Front-end and UI development and still going strong improving prowess.
                <br>
                <br>
                I finished my Masters of Engineering in Mechanical Engineering from N.I.T. Hamirpur(H.P.) in 2018 and taught my-self Front-end development in summer 2020 with Javascript as my second programming language.
                </h4>
              </div>
              
              
            </div>
            
     </v-container> 
    </div>
  </div> 
</template>

<style scoped>
  .home{
    width: 100%;
    height: fit-content;
    background-color: white;
  }
  /* .home-body{
    background-color:  rgba(233, 223, 223, 0.158);
  } */
  .headline{
    margin: auto;
    width: 80%;
    height: fit-content;
  }
  .profile-paragraph{
    width: 100%;
    padding: 4%;
    height: fit-content;
    display: flex;
    flex-direction: row;
    justify-content: center;
  }
  .bio{
    width: 40%;
    padding: 1%;
  }
  @media(max-width:600px){
    .home{
      display: flex;
      flex-direction: column;
    }
    .profile-paragraph{
      display: flex;
      flex-direction: column;
    }
    .bio{
      width: 100%;
    }
  }
</style>
