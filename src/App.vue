<template>
  <div id="app">
    <Nav/>
    <Main/>
    <InfoPanel/>
    <Description/>
  </div>
</template>
<script>
import Main from "./components/Main";
import Nav from "./components/Nav";
import InfoPanel from "./components/InfoPanel";
import Description from "./components/Description";
export default {
  name: "App",
  components: { Main, Nav, InfoPanel, Description }
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
  overflow: hidden;
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
