<template>
  <div class="description">
    <div class="content-wrapper">
      <h1>Join The Best Producer Cummunity</h1>
      <p>
        Raw Impulse is a entry point for small Music Producer to
        <br>get advices and grow.
        Additionaly you get in touch with
        <br>others and get featured on our soundcloud.
      </p>
      <button>Get Started Now</button>
    </div>
    <div class="release-box">
      <div class="black box"></div>
      <div class="yellow box">
        <h1>
          NEW
          <br>RELEASES.
        </h1>
        <p>
          Check out our newest
          <br>Releases on Soundcloud
          <br>to get featured.
        </p>
      </div>
    </div>
    <div class="links">
      <ul>
        <li>
          <a href="#">SoundclouD</a>
        </li>
        <li>
          <a href="#">Discord</a>
        </li>
        <li>
          <a href="#">Instagram</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Description"
};
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css?family=Roboto:500");
$main-color: #e5c764;
.description {
  padding: 32pt 44pt 42pt 28pt;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  color: black;
  display: grid;
  grid-template-columns: 42% 27% 2%;
  grid-template-rows: 60vh 40vh;
  position: relative;
  .content-wrapper {
    position: relative;
    height: 100%;
    h1 {
      font-weight: 700;
      font-size: 20pt;
    }
    p {
      margin-top: 31pt;
      font-weight: 600;
      font-size: 14pt;
      line-height: 19pt;
    }
    button {
      background: none;
      color: $main-color;
      font-weight: 500;
      box-shadow: none;
      border: none;
      outline: none;
      font-size: 16pt;
      font-family: "Roboto", "Courier New", Courier, monospace;
      letter-spacing: 0;
      position: absolute;
      bottom: 0;
      cursor: pointer;
    }
  }
  .release-box {
    display: inline;
    margin-left: 70pt;
    position: relative;
    .box {
      width: 214pt;
      height: 214pt;
      position: absolute;
    }
    .yellow {
      background: $main-color;
      z-index: 10;
      top: 25pt;
      left: 25pt;
      padding-left: 20px;
      padding-top: 20px;
    }
    .black {
      background: black;
      z-index: -2;
    }
    h1 {
      color: black;
      font-weight: 700;
      font-size: 30pt;
      z-index: 11;
      line-height: 40pt;
    }
    p {
      font-weight: 500;
      font-size: 14pt;
      color: white;
      line-height: 19pt;
      margin-top: 26pt;
    }
  }
  .links {
    z-index: 600;
    transform: rotate(-90deg);

    margin-left: 650px;
    margin-top: 40px;
    li {
      list-style-type: none;
      margin-right: 20px;
      display: inline;
      a {
        font-size: 16pt;
        font-family: "Roboto", "Gill Sans", "Gill Sans MT", Calibri,
          "Trebuchet MS", sans-serif;
        color: $main-color;
      }
    }
  }
}
</style>
