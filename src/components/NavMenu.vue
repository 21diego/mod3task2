<template>
  <div >
    <router-view/>
    <div id="nav" class="fixed-bottom bg-white d-flex justify-content-around">
      <router-link to="/user"><img src="../assets/user.png" alt="" width="60" height="60"></router-link>
      <router-link to="/"><img src="../assets/home.png" alt="" width="60" height="60"></router-link>
      <router-link to="/notification"><img src="../assets/wechat.png" alt="" width="65" height="65"></router-link>
      <router-link to="/option"><img src="../assets/cog.png" alt="" width="60" height="60"></router-link>
    </div>
    
  </div>
</template>

<script>
  export default {
    name: "NavMenu"
  }
</script>

<style lang="scss" scoped>

</style>