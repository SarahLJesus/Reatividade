<script setup>
  import { ref } from 'vue';

  const contador = ref(0);

  function incrementar() {
    contador.value++;
  }
  function decrementar() {
    contador.value--;
  }

</script>

<template>
  <button @click="incrementar">{{ contador }} </button>
  <button @click="decrementar">{{ contador }} </button>
</template>
