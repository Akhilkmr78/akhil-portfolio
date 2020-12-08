<template>
  <div class="container mt-n6 home-body">
    <div class="home pa-2">
    <v-container>
      <div class="projects-area">
        <v-card
          class="mx-auto project-card"
          max-width="440"
          min-width="280"
        >
          <v-card-text>
            <v-img 
            src="../assets/Keep.png"
            height="180"
            ></v-img>
            <div class="text--primary">
              <h3 style="font-weight: 700;" class="text-center mt-2">Keep</h3>
            </div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              icon
              large
              color="black"
              href="https://github.com/Akhilkmr78/keep"
              target="_blank"
            >
              <v-icon>mdi-github</v-icon>
            </v-btn>
            <v-btn
              icon
              large
              color="black"
              href="https://keep-clone-d2d76.web.app"
              target="_blank"
            >
              <v-icon>mdi-web</v-icon>
            </v-btn>
            <v-btn
              text
              color="blue lighten-3"
              @click="reveal = true"
            >
              Read More
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <v-card
              v-if="reveal"
              class="transition-fast-in-fast-out v-card--reveal"
              style="height: 100%;"
            >
              <v-card-text class="pb-0">
                <p class="title text--primary">
                  Keep
                </p>
                <p class="project-description">Restructured version of a popular note keeping app of Google. I've tried to provide users with a simple sign-up flow and data customizable according to their credentials only. This Keep clone can be considered as full blown CRUD application; capable of organizing data efficiently within a effortless formation.</p>
                <span class="mr-6">Technologies Used</span>
                <span class="mx-2 hvr-grow"><img src="../assets/Vue.svg" alt="" height="22" width="22"></span>
                <span class="mx-2 hvr-grow"><img src="../assets/Vuetify.svg" alt="" height="22" width="22"></span>
                <span class="mx-2 hvr-grow"><img src="../assets/Firebase.svg" alt="" height="22" width="22"></span>
              </v-card-text>
              <v-card-actions class="pt-0">
                <v-btn
                  icon
                  x-small
                  color="blue lighten-3"
                  @click="reveal = false"
                  class="mx-2 mt-6 hvr-icon-spin"
                >
                <v-icon class="hvr-icon">mdi-arrow-left</v-icon>
                  
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-expand-transition>
        </v-card>

        <v-card
          class="mx-auto project-card"
          max-width="440"
          min-width="320"
        >
          <v-card-text>
            <v-img 
            src="../assets/fireboard.png"
            height="180"
            ></v-img>
            <div class="text--primary">
              <h3 style="font-weight: 700;" class="text-center mt-2">Fireboard</h3>
            </div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              icon
              large
              color="black"
              href="https://github.com/Akhilkmr78/Fireboard1"
              target="_blank"
            >
              <v-icon>mdi-github</v-icon>
            </v-btn>
            <v-btn
              icon
              large
              color="black"
              href="https://akhilkmr78.github.io/Fireboard1/"
              target="_blank"
            >
              <v-icon>mdi-web</v-icon>
            </v-btn>
            <v-btn
              text
              color="blue lighten-3"
              @click="reveal1 = true"
            >
              Read More
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <v-card
              v-if="reveal1"
              class="transition-fast-in-fast-out v-card--reveal"
              style="height: 100%;"
            >
              <v-card-text class="pb-0">
                <p class="title text--primary">
                  Fireboard
                </p>
                <p class="project-description">Fireboard represents a social media ananlysis website with all the modern features required, from sign-up flow to admin-dashboard. The intent is to develop feasible UI designs which are cross-device responsive and styled for best user experience possible. </p>
                <span class="mr-6">Technologies Used</span>
                <span class="mx-2 hvr-grow"><img src="../assets/HTML5.svg" alt="" height="22" width="22"></span>
                <span class="mx-2 hvr-grow"><img src="../assets/CSS3.svg" alt="" height="22" width="22"></span>
                <span class="mx-2 hvr-grow"><img src="../assets/Javascript.svg" alt="" height="22" width="22"></span>
                 <span class="mx-2 hvr-grow"><img src="../assets/Materialize.svg" alt="" height="22" width="22"></span>
              </v-card-text>
              <v-card-actions class="pt-0">
                <v-btn
                  icon
                  x-small
                  color="blue lighten-3"
                  @click="reveal1 = false"
                  class="mx-2 mt-6 hvr-icon-spin"
                >
                <v-icon class="hvr-icon" color="blue lighten-3">mdi-arrow-left</v-icon>
                  
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-expand-transition>
        </v-card>

         <v-card
          class="mx-auto project-card"
          max-width="440"
          min-width="320"
        >
          <v-card-text>
            <v-img 
            src="../assets/weather app.png"
            height="180"
            ></v-img>
            <div class="text--primary">
              <h3 style="font-weight: 700;" class="text-center mt-2">Weatherable</h3>
            </div>
          </v-card-text>
          <v-card-actions>
             <v-btn
              icon
              large
              color="black"
              href="https://github.com/Akhilkmr78/Weatherable"
              target="_blank"
            >
              <v-icon>mdi-github</v-icon>
            </v-btn>
            <v-btn
              icon
              large
              color="black"
              href="https://akhilkmr78.github.io/Weatherable/"
              target="_blank"
            >
              <v-icon>mdi-web</v-icon>
            </v-btn>
            <v-btn
              text
              color="blue lighten-3"
              @click="reveal2 = true"
            >
              Read More
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <v-card
              v-if="reveal2"
              class="transition-fast-in-fast-out v-card--reveal"
              style="height: 100%;"
            >
              <v-card-text class="pb-0">
                <p class="title text--primary">
                  Weatherable
                </p>
                <p class="project-description">A fun weather app which delivers the live weather conditions along with the day/night status of worldwide cities. This beautiful app is a visual gem which makes live api requests to popular accuweather database and provide accurate info. of the particular city all over the world.</p>
                <span class="mr-6">Technologies Used</span>
                <span class="mx-2 hvr-grow"><img src="../assets/HTML5.svg" alt="" height="22" width="22"></span>
                <span class="mx-2 hvr-grow"><img src="../assets/Materialize.svg" alt="" height="22" width="22"></span>
                <span class="mx-2 hvr-grow"><img src="../assets/Javascript.svg" alt="" height="22" width="22"></span>
                 
              </v-card-text>
              <v-card-actions class="pt-0">
                <v-btn
                  icon
                  x-small
                  color="blue lighten-3"
                  @click="reveal2 = false"
                  class="mx-2 mt-6 hvr-icon-spin"
                >
                   <v-icon class="hvr-icon" color="blue lighten-3">mdi-arrow-left</v-icon>
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-expand-transition>
        </v-card>      
      </div>
      <div class="mobile-projects d-flex d-sm-none mt-2 mx-auto">
           <v-card
          class="mx-auto mt-2"
          min-width="200"
        >
          <v-img
            src="../assets/Keep.png"
            height="200px"
          ></v-img>

          <v-card-title class="title text--primary">
            Keep
          </v-card-title>
          

          <v-card-actions>
            <v-btn
              icon
              small
              color="black"
              href="https://github.com/Akhilkmr78/keep"
              target="_blank"
            >
              <v-icon>mdi-github</v-icon>
            </v-btn>
            <v-btn
              icon
              small
              color="black"
              href="https://keep-clone-d2d76.web.app"
              target="_blank"
            >
              <v-icon>mdi-web</v-icon>
            </v-btn>

            
            <v-spacer></v-spacer>

            <v-btn
              icon
              @click="show = !show"
            >
              <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-divider></v-divider>

              <v-card-text>
                <p class="text-justify project-description">Restructured version of a popular note keeping app of Google. I've tried to provide users with a simple sign-up flow and data customizable according to their credentials only. This Keep clone can be considered as full blown CRUD application; capable of organizing data efficiently within a effortless formation.</p>
                <span class="mr-2">Technologies Used</span>
                <span class="mx-1 hvr-grow"><img src="../assets/Vue.svg" alt="" height="22" width="22"></span>
                <span class="mx-1 hvr-grow"><img src="../assets/Vuetify.svg" alt="" height="22" width="22"></span>
                <span class="mx-1 hvr-grow"><img src="../assets/Firebase.svg" alt="" height="22" width="22"></span>
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
        <!-- --Card One Mobile-- -->

        <v-card
          class="mx-auto mt-2"
          min-width="200"
        >
          <v-img
            src="../assets/fireboard.png"
            height="200px"
          ></v-img>

          <v-card-title class="title text--primary">
            Fireboard
          </v-card-title>


          <v-card-actions>
            <v-btn
              icon
              small
              color="black"
              href="https://github.com/Akhilkmr78/Fireboard1"
              target="_blank"
            >
              <v-icon>mdi-github</v-icon>
            </v-btn>
            <v-btn
              icon
              small
              color="black"
              href="https://akhilkmr78.github.io/Fireboard1/"
              target="_blank"
            >
              <v-icon>mdi-web</v-icon>
            </v-btn>
            

            <v-spacer></v-spacer>

            <v-btn
              icon
              @click="show1 = !show1"
            >
              <v-icon>{{ show1 ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show1">
              <v-divider></v-divider>

              <v-card-text>
                 <p class="text-justify project-description">Fireboard represents a social media ananlysis website with all the modern features required, from sign-up flow to admin-dashboard. The intent is to develop feasible UI designs which are cross-device responsive and styled for best user experience possible.</p>
                <span class="mr-2">Technologies Used</span>
                <span class="mx-1 hvr-grow"><img src="../assets/HTML5.svg" alt="" height="22" width="22"></span>
                <span class="mx-1 hvr-grow"><img src="../assets/Materialize.svg" alt="" height="22" width="22"></span>
                <span class="mx-1 hvr-grow"><img src="../assets/Javascript.svg" alt="" height="22" width="22"></span>
                <span class="mx-1 hvr-grow"><img src="../assets/CSS3.svg" alt="" height="22" width="22"></span>
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
        <!-- --Card Two Mobile-- -->

        <v-card
          class="mx-auto mt-2"
          min-width="200"
        >
          <v-img
            src="../assets/weather app.png"
            height="200px"
          ></v-img>

          <v-card-title class="title text--primary">
            Weatherable
          </v-card-title>

          

          <v-card-actions>
            <v-btn
              icon
              small
              color="black"
              href="https://github.com/Akhilkmr78/Weatherable"
              target="_blank"
            >
              <v-icon>mdi-github</v-icon>
            </v-btn>
            <v-btn
              icon
              small
              color="black"
              href="https://akhilkmr78.github.io/Weatherable/"
              target="_blank"
            >
              <v-icon>mdi-web</v-icon>
            </v-btn>
            
            <v-spacer></v-spacer>

            <v-btn
              icon
              @click="show2 = !show2"
            >
              <v-icon>{{ show2 ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show2">
              <v-divider></v-divider>

              <v-card-text>
                 <p class="text-justify project-description">A fun weather app which delivers the live weather conditions along with the day/night status of worldwide cities. This beautiful app is a visual gem which makes live api requests to popular accuweather database and provide accurate info. of the particular city all over the world.</p>
                <span class="mr-2">Technologies Used</span>
                <span class="mx-1 hvr-grow"><img src="../assets/HTML5.svg" alt="" height="22" width="22"></span>
                <span class="mx-1 hvr-grow"><img src="../assets/Materialize.svg" alt="" height="22" width="22"></span>
                <span class="mx-1 hvr-grow"><img src="../assets/Javascript.svg" alt="" height="22" width="22"></span>
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
        <!-- --Card Three Mobile-- -->
      </div>
     </v-container> 
    </div>
  </div>
</template>

<script>
  export default {
    data: () => ({
      reveal: false,
      reveal1: false,
      reveal2: false,
      show: false,
      show1: false,
      show2: false
    }),
  }
</script>

<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@300&display=swap');
*{
  font-family: 'Nunito Sans', sans-serif;
  font-weight: 500;
}
  .home{
    width: 100%;
    height: fit-content;
    background-color: white;
  }
  /* .home-body{
    background-color:  rgba(233, 223, 223, 0.158);
  } */
  .projects-area{
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 2%;
  }


  @media(max-width:1266px){
    .projects-area{
      display: grid;
    grid-template-columns: 1fr;
    }
  }

  @media(max-width: 550px){
     .projects-area{
       display: none;
     }
     .project-card{
       width: 90%;
       height: fit-content;
     }
     .mobile-projects{
       width: 100%;
       height: 100%;
       display:flex;
       flex-direction: column;
     }
  }

  .v-card--reveal {
  bottom: 0;
  opacity: 1 !important;
  position: absolute;
  width: 100%;
}
.project-description{
  font-size: 1rem;
  font-weight: 600;
}

</style>
