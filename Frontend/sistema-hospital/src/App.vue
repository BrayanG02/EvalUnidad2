<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <RouterView />
  <div >
  <PiePagina />
  </div>
</template>

<script>
import PiePagina from './components/piePagina.vue'

export default {
components: {
    PiePagina
    }
}
</script>





