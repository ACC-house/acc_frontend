<script setup>
import NavBar from '../components/NavBar.vue';
</script>

<template>
  <NavBar/>
  <div>
    
    <div class="d-flex flex-column align-items-center">
      
      <div class="vh-50">
        <img src="@/assets/photo.jpg" class="img-fluid" alt="Mi Foto">
      </div>
      
      <div class="container mt-15">
        <div class="row">
            <div class="col-md-6 mb-4">
                <div class="superpuesta-container">
                    <img src="@/assets/work1.png" class="superpuesta-foto" alt="Superposición">
                    <div class="borde-verde"></div>
                    <div class="borde-verde-abajo"></div>
                </div>
            </div>
        </div>
    </div>
      
      <div class="contenido-principal mt-10">
        <h1 class="titulo text-center">¿Quieres reformar tu casa, local u obra nueva?</h1>
        <p class="text text-center mt-4 mb-4">Reforma  tu casa , local  sin complicaciones. En ACC Reformas, te ayudamos reformar  lo que necesites de forma rápida y segura. Sin intermediarios ni comisiones ocultas. ¡Obtén una oferta justa hoy mismo!</p>
      </div>
    </div>
  </div>
  


</template>

<style scoped>

  .titulo {
  color: rgb(46, 47, 47); 
  font-size: 25px; 
}

body {
  background-color: white;
  overflow-y: hidden;
}
.superpuesta-container {
            position: relative;
        }

        .superpuesta-foto {
            display: block;
        }

        .borde-verde {
            position: absolute;
            width: 13px; 
            height: 100%; 
            background-color: rgb(127, 170, 157); 
            top: 0; 
            right: 0; 
        }

        .borde-verde-abajo {
            position: absolute;
            width: 100%; 
            height: 5px; 
            background-color: rgb(127, 170, 157) ; 
            bottom: 0; 
            left: 0; 
        }












</style>