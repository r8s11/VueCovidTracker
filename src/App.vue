<template>
  <Header />
  <div class="container mx-auto">
    <router-view/>
  </div>
  
</template>

<script lang="ts">
import Header from '@/components/Header'

export default {
  components: {
    Header,
  }
}
</script>
