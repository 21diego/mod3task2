<template>
  <div class="home">
    <div class="sticky-top">
      <h1 class="bg-success mb-0">NYSL-APP</h1>
      <Header titulo="Upcoming Events"></Header>
    </div>
    <MapaBox class="m-0 p-0"></MapaBox>
    <MapaBox class="m-0 p-0"></MapaBox>
    <MapaBox class="m-0 p-0"></MapaBox>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import MapaBox from '@/components/MapaBox.vue'

export default {
  name: 'Home',
  components: {
    Header,
    MapaBox
  }
}
</script>
