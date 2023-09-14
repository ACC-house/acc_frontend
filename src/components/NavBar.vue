<script setup>


</script>



<template>
    <div class="container mt-5">
      <div class="row justify-content-center">
        <div class="col-md-6">
          
          <div class="cuadrado">
            <p class="frase font-weight-boldtexto-sombreado ">Reformamos el lugar perfecto para ti</p>
            <div class="d-flex justify-content-center">
           <button class="btn btn-outline-light mr-2" @click="mostrarMensaje('Botón 1 presionado')">Trabajos</button>
          <button class="btn btn-outline-light" @click="mostrarMensaje('Botón 2 presionado')">Presupuestos</button> 
        </div>
            
          
            
          </div>
        </div>
      </div>
    </div>
  </template>

<style scoped>
.cuadrado {
  background-color: rgba(100, 119, 117, 0.37); /* Fondo con opacidad */
  border-radius: 10px;
  padding: 40px;
  color: rgb(243, 236, 236);
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -40%);
}

.frase {
  font-size: 37px;
  margin-top: 20px;
 font-family: 'Ubuntu', sans-serif;;
}
</style>