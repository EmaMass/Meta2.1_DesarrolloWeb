<script setup>
import AppHeader from './components/AppHeader.vue'
import TarjetaConImagen from './components/TarjetaConImagen.vue'
import TablaDeDatos from './components/TablaDeDatos.vue'
import AppFooter from './components/AppFooter.vue'
</script>

<template>
  <div>
    <!-- Encabezado -->
    <AppHeader />

    <!-- Tarjetas -->
    <div class="container my-5">
      <div class="row">
        <div class="col">
          <TarjetaConImagen
            img="https://picsum.photos/900/300"
            titulo="Titulo 1"
            texto="Texto de la Carta 1"
          />
        </div>
        <div class="col">
          <TarjetaConImagen
            img="https://picsum.photos/899/300"
            titulo="Titulo 2"
            texto="Texto de la Carta 2"
          />
        </div>
      </div>
    </div>

    <!-- Tabla -->
    <div class="container my-5">
      <TablaDeDatos />
    </div>

    <!-- Botón -->
    <div class="container d-flex align-items-center justify-content-center mb-5">
      <button type="button" class="btn btn-primary">Boton</button>
    </div>

    <!-- Footer -->
    <AppFooter />
  </div>
</template>

<style scoped></style>
