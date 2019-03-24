<template>
  <div class="search-wrapper">
    <input type="text" placeholder="Search Products">
    <font-awesome-icon icon="search"/>
  </div>
</template>

<script >
export default {
  name: "Search"
};
</script>

<style scoped lang="scss">
$main-color: #e5c764;
.search-wrapper {
  background: #000;
  width: 100%;
  height: 17%;
  overflow: hidden;
  position: absolute;
  bottom: 0%;
  transition: all 4000ms ease-in-out;
  input {
    margin-top: 30px;
    margin-left: 30px;
    border-top: none;
    border-left: none;
    border-right: none;
    background: transparent;
    padding-bottom: 5px;
    color: white;
    font-size: 1.1rem;
    position: relative;
    &:focus {
      border-bottom: $main-color solid;
      outline: none;
    }
  }
  svg {
    position: absolute;
    color: grey;
    top: 32px;
    left: 220px;
  }
}
</style>


