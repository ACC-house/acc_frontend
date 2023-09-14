<script>
import { RouterView } from 'vue-router'
import NavComponent from './components/NavComponent.vue';
import NavBar from './components/NavBar.vue';



export default {
  name: 'App',
  components: {
    RouterView,
    NavComponent,
    NavBar

}
}

</script>

<template>
 
 <NavBar/>
<NavComponent/>
 <RouterView/>
 
 
 

  
</template>

<style scoped>





  

</style>
