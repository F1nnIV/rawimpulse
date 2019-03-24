<template>
  <div class="wrapper">
    <nav>
      <ul>
        <li>
          <a href="#">License</a>
          <a href="#">Guides</a>
          <a href="#">Terms of use</a>
          <a href="#">Privacy Police</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Infopanel"
};
</script>

<style lang="scss" scoped>
$main-color: #e5c764;
@import url("https://fonts.googleapis.com/css?family=Roboto:700");
.wrapper {
  background: black;
  background: url(../assets/mixer.jpg) no-repeat;
  background-size: cover;
  font-family: "Roboto", Tahoma, Geneva, Verdana, sans-serif;
  position: relative;
  ul {
    position: absolute;
    bottom: 15px;
    width: 100%;
  }
  a {
    margin-bottom: 24px;
    display: block;
    color: white;
    font-size: 1.3rem;
    align-content: center;
    margin-left: 22%;
    transition: color 350ms ease-in-out;
    &:hover {
      color: $main-color;
    }
  }
}
</style>

