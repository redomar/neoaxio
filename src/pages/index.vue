<template>
  <div class="content">
    <div>
      <h1 class="title">neoaxio</h1>
      <Feature />
      <FeatureParticles />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
// import FeatureParticles from '../components/Demo.vue'
// import Particles from 'particles.vue'

// Vue.use(Particles)
export default Vue.extend({
  // components: { FeatureParticles }
})
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
*/

.content {
  @apply min-h-full  justify-center items-center text-center;
}

.title {
  @apply text-3xl bg-red-500;
}
</style>
