<template>
  <div class="home">
    <div class="sticky-top">
      <h1 class="bg-success mb-0">NYSL-APP</h1>
      <Header titulo="Notifications"></Header>
    </div>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'

export default {
  name: 'Notification',
  components: {
    Header
  }
}
</script>