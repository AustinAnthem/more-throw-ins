<template>
  <div id="app">
    <title>Austin Soccer Votes</title>

    <div id="maintable">
      <table>
        <tr>
          <Props2020 />
        </tr>
        <tr>
          <HowToVote />
        </tr>
        <tr>
          <Disclaimer />
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
import Disclaimer from "./components/Disclaimer.vue";
import Props2020 from "./components/Props2020.vue";
import HowToVote from "./components/HowToVote.vue";

export default {
  name: "App",
  components: {
    Disclaimer,
    Props2020,
    HowToVote,
  },
  created() {
    document.title = "Austin Soccer Votes";
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Raleway&display=swap");
@import url('https://fonts.googleapis.com/css2?family=Paytone+One&display=swap');
#app {
  font-family: Raleway, Paytone One, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: white;
  margin: 0;
  background-color: #00b140;
  background-size: 100%;
  background-blend-mode: darken;
  background-repeat: no-repeat;
  background-position: center;
  align-items: center;
  justify-content: center;
  background-clip: padding-box;
}
#maintable {
  max-width: 80%;
  text-align: center;
  margin-left: 10%;
  margin-right: 10%;
  display: flex;
}
* {
  margin: 0;
}
html {
  background-color: #00b140;
}

h1 {
  color: #000000;
  font-size: 40px;
}

html a:link,
a:visited {
  color: #000000;
}

@media only screen and (max-width: 760px),
  (min-device-width: 768px) and (max-device-width: 1024px) {
  /* Force table to not be like tables anymore */
  #maintable {
    display: flex;
    max-width: 100%;
    width: 94%;
    margin-left: 3%;
    margin-right: 3%;
  }
  table,
  thead,
  tbody,
  th,
  td,
  tr {
    display: block;
    width: 100%;
  }
  td {
    /* Behave  like a "row" */
    position: relative;
    width: 95%;
  }
  h1 {
    color: #000000;
    font-size: 20px;
  }
}
</style>
