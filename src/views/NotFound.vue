<template>
  <div id="container">
    <h1>404</h1>
    <h2>There isn't anything here</h2>
  </div>
</template>

<script>
export default {
  name: "404"
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: 0 0;
}

body {
  line-height: 1;
}

* {
  box-sizing: border-box;
}

html {
  background-color: #fbfbfb;
  color: #343a40;
  font-size: 16px;
  font-family: "Open Sans", sans-serif;
}

@media screen and (max-width: 600px) {
  html {
    font-size: 10px;
  }
}

#container {
  width: calc(100% - 100px);
  max-width: 700px;
  min-width: 300px;
  margin: 0 auto;
  padding: 50px;
}

h1 {
  font-size: 16rem;
}

h2 {
  font-size: 6rem;
  color: #343a40bf;
}

@font-face {
  font-family: "Open Sans";
  font-style: normal;
  font-weight: 700;
  src: local("Open Sans Bold"), local("OpenSans-Bold"),
    url("https://fonts.gstatic.com/s/opensans/v10/k3k702ZOKiLJc3WVjuplzOgdm0LZdjqr5-oayXSOefg.woff2")
      format("woff2");
}
</style>
