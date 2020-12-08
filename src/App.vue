<template>
  <v-container>
    <v-app>
      <hello-world></hello-world>  
    <v-main>
      <v-container>
        <router-view></router-view>
      </v-container>
    </v-main>
    <v-footer padless color="white">
    <v-col
      class="text-center mt-2"
      cols="12"
      
    >
      &#169;{{ new Date().getFullYear() }}
    </v-col>
  </v-footer>
  </v-app>
 </v-container> 
</template>

<script>

import HelloWorld from './components/HelloWorld.vue';
export default {
  name: "App",
  components: {
    HelloWorld
  },
  data: () => ({
    //
  })
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@300&display=swap');
*{
  font-family: 'Nunito Sans', sans-serif;
  font-weight: 500;
}
body::-webkit-scrollbar{
       width: 6px;
   }
   body::-webkit-scrollbar-track{
       color: rgb(192, 191, 179);
   }
   body::-webkit-scrollbar-thumb{
       background:rgb(192, 191, 179);
   }
   body{
      background-color: rgba(233, 223, 223, 0.158);
   }
</style>
