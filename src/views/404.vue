<template>
  <div id="app">
    <Nav/>
    <InfoPanel/>
  </div>
</template>
<script>
import Main from "./components/Main";
import Nav from "./components/Nav";
import InfoPanel from "./components/InfoPanel";
export default {
  name: "App",
  components: { Main, Nav, InfoPanel }
};
</script>

<style lang="scss">
$main-color: #e5c764;
* {
  padding: 0%;
  margin: 0%;
  box-sizing: border-box;
}
body {
  height: 100vh;
  width: 100%;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  #app {
    display: grid;
    grid-template-columns: 25% 75%;
    grid-template-rows: 60vh 40vh;
  }
  a {
    text-decoration: none;
  }
}
</style>
