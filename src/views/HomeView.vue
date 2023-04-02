<template>
 <banner />
  <div class="main-container">
    <h1>Monte o seu Burguer:</h1>
    <burgerform />
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue'
import Burgerform from '@/components/Burgerform.vue'


export default {
  name: "Home",
  components: {
    Banner,
    Burgerform,
  }
}
</script>
