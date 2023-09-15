<script>
import { RouterView } from 'vue-router'
import NavComponent from './components/NavComponent.vue';

import FooterWorks from './components/FooterWorks.vue'


export default {
  name: 'App',
  components: {
    RouterView,
    NavComponent,
    
    FooterWorks

}
}

</script>

<template>
 

 <NavComponent/>
 <RouterView/>
 <FooterWorks/>
 
 
 

  
</template>

<style scoped>





  

</style>
