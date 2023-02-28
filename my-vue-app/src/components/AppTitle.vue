<script>
export default {
  data() {
    return {
      description: 'La mia prima app con Vite!'
    }
  }
}
</script>

<template>
  <div class="titolo">
    {{ description }}
  </div>

 
</template>

<style>
.titolo {
  color: cornflowerblue;
  font-size: 40px;
}
</style>