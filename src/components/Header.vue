<template>
  <header>
      <Navigation/>
  </header>
</template>

<script>
import Navigation from '@/components/Navigation.vue'
export default {
    components: {
      Navigation,
    }
}
</script>

<style>
 @media only screen and (max-width: 800px) {
   header {
    position: absolute;
    bottom: 0;
    width: 100%;
   }
 }
</style>