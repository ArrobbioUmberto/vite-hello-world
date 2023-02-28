<script>
// 1. importare il componente
// import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
export default {
  components: {
    // 2. registrare il componente che abbiamo importato
    AppHero,
    // AppTitle
  },
  data() {
    return {
      
    }
  },
  methods: {
    
  }
}
</script>

<template>

  <!-- 3. utilizzo il componente -->
  <div>
    <AppHero></AppHero>
  </div>
  <!-- <AppTitle></AppTitle> -->
  
  
 


</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
