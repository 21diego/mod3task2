<template>
  <div class="bg-danger">
    <h1 class="mb-0">{{titulo}}</h1>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    titulo: String
  }
}
</script>
