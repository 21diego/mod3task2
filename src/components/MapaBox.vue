<template>
  <div class="bg-dark">
    <h3 class="text-white">Nombre locacion</h3>
    <div id="mapbox">
      <iframe id="mapan" class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2969.337739384588!2d-87.64837698511293!3d41.907097779219825!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x880fd33af0e6ccc3%3A0x26c81c1d557667da!2s1409%20N%20Ogden%20Ave%2C%20Chicago%2C%20IL%2060610%2C%20EE.%20UU.!5e0!3m2!1ses-419!2sar!4v1579206712107!5m2!1ses-419!2sar" width="340" height="250" frameborder="0" style="border:0;" allowfullscreen=""></iframe>
    </div>
    <p class="text-white">direccion</p>
  </div>
</template>

<script>
export default {
  name: "MapaBox"
}
</script>