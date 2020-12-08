<template>
  <div class="container">
     <v-navigation-drawer
      v-model="boxASelected"
      absolute
      temporary
      overlay-opacity="0.001"
      class="d-flex d-sm-none"
    >
      <v-list-item>
        <v-list-item-avatar>
          <v-img src="../assets/Akhil.jpg"></v-img>
        </v-list-item-avatar>

        <v-list-item-content>
          <v-list-item-title class="text-capitalize avatar-name" @click="takeToAbout">Akhil Kumar</v-list-item-title>
        </v-list-item-content>
      </v-list-item>

      <v-divider></v-divider>

      <v-list nav shaped>
        <v-list-item link @click="takeToProjects">
          <v-list-item-icon>
            <v-icon color="blue lighten-3">mdi-notebook</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title class="nav-links">Projects</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item link @click="takeToContacts">
          <v-list-item-icon>
            <v-icon color="blue lighten-3">mdi-connection</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title class="nav-links">Contact</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer> 
     <v-app-bar flat color="white">
      <div class="mobile-view">
        <v-toolbar-title class="app-title" @click="takeToAbout">AKHIL KUMAR</v-toolbar-title>
        <div class="hamburger hamburger--squeeze d-flex d-sm-none" :class="boxASelected ? 'is-active' : 'no-active'" @click="changeHam">
          <div class="hamburger-box">
            <div class="hamburger-inner"></div>
          </div>
        </div>
      </div> 
       
       
       <v-spacer></v-spacer>
      <div class="align-center mx-auto d-none d-sm-flex">
        <v-tabs centered color="blue lighten-3" slider-size="4" >
    <v-tab class="text-capitalize" to="/">
      About
    </v-tab>
    <v-tab class="text-capitalize" to="/about">
      Projects
    </v-tab>
    <v-tab class="text-capitalize" to="/contact">
      Contact
    </v-tab>
  </v-tabs>
      </div> 
    </v-app-bar>
    
  </div>  
</template>

<script>
export default {
  data(){
    return {
      boxASelected :  false
    }
  },
  methods: {
    takeToAbout(){
      this.$router.push('/')
    },
    changeHam(){
      this.boxASelected = !this.boxASelected
    },
    takeToProjects(){
      this.$router.push('/about')
    },
    takeToContacts(){
      this.$router.push('/contact')
    }
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=PT+Mono&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@300&display=swap');
  .app-title{
    cursor: pointer;
     font-family: 'PT Mono', monospace;
    font-weight: 600;
    font-size: 1rem;
  }
  .app-title:hover{
    color: #90CAF9;
  }
  .avatar-name{
    font-family: 'Nunito Sans', sans-serif;
    font-weight: 600;
  }
  .nav-links{
    font-family: 'Nunito Sans', sans-serif;
    font-weight: 600;
  }

  @media(max-width:600px){
    .mobile-view{
      width: 100%;
      display:flex;
      flex-direction: row;
      align-items: center;
      justify-content: space-between;
    }
    
  }
</style>





