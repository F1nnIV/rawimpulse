<template>
  <aside class="aside" style="
position:relative">
    <div class="nav-wrapper">
      <font-awesome-icon icon="ellipsis-h" class="fa-2x"/>
      <nav>
        <h3>New Releases</h3>
        <hr>
        <p>Singles</p>
        <p>EP's</p>
        <p>Sample Packs</p>
        <p>Articles</p>
      </nav>
    </div>
    <Search/>
  </aside>
</template>

<script>
import Search from "./Search";
export default {
  name: "Nav",
  components: { Search }
};
</script>

<style scoped lang="scss">
@import url("https://fonts.googleapis.com/css?family=Roboto:500");
.nav-wrapper {
  padding: 44px 32px;
  nav {
    padding: 10px 18px;
    &,
    .fa-4x {
      height: 83%;
    }
    hr {
      margin-bottom: 35px;
      color: #f5f5f5;
      width: 20px;
      border-bottom: 4px;
    }
    p {
      margin-bottom: 36px;
      font-family: "Roboto", "Courier New", Courier, monospace;
    }
  }
}
</style>
