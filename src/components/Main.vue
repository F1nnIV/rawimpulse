<template>
  <div class="main">
    <!-- <img src="main_piano.jpg" alt> -->
    <h1 class="heading">RAW</h1>
    <h1 class="heading light">IMPULSE</h1>
  </div>
</template>

<script>
export default {
  name: "Main"
};
</script>

<style scoped lang="scss">
.main {
  background: url(../assets/main_piano.jpg) no-repeat;
  position: relative;
  overflow: hidden;
  background-size: cover;
  h1 {
    color: #fff;
    font-size: 130px;
    z-index: 2;
    position: absolute;
    top: 190px;
    left: 30px;
  }
  .light {
    color: transparent;
    -webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: white;
    z-index: 0;
    top: calc(150px + 100px);
    left: 150px;
  }
}
</style>
