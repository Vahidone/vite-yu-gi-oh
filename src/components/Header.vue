<script>
export default {
  name:'Header'
}
</script>


<template>
  <header class="d-flex align-items-center" >
    <img src="/public/Yugioh_anime_logo.webp">
    <h2>YU-GI-OH Api</h2>
  </header>
</template>



<style lang="scss" scoped>
@use '../scss/main' as *;
@use "../../scss/partials/variables" as *;

  header{
    width: 100%;
    height: 60px;
    padding-left: 20px;
    background-color: $bg-white;
    img {
      width: 75px;
      height: 25px;
      margin-right: 10px;
    }
  }
</style>