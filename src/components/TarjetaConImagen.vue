<template>
  <div class="card">
    <img :src="img" class="card-img-top" />
    <div class="card-body">
      <h5 class="card-title">{{ titulo }}</h5>
      <p class="card-text">{{ texto }}</p>
    </div>
  </div>
</template>

<script setup>
defineProps({
  img: String,
  titulo: String,
  texto: String
})
</script>