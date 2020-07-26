<template>
  <router-view />
</template>

<script lang="ts">
import { ref, provide } from 'vue'

export default {
  name: 'App',
  setup(){
    const menuVisible = ref(false)
    provide('menuVisible', menuVisible) // set
  }
}
</script>
