<template>
  <Appheader />
  <div class="maindiv">
    <AppCard1 />
  </div>
  <AppCard2 />
  <AppCard5 />
  <AppCardplat />
  <AppCard6 />
  <AppCard7 />
  <Appfooter />
</template>

<script>
import Appheader from "./components/Appheader.vue";
import Appfooter from "./components/Appfooter.vue";
import AppCard1 from "./components/AppCard1.vue";
import AppCard2 from "./components/AppCard2.vue";
import AppCard7 from "./components/AppCard7";
import AppCard6 from "./components/AppCard6";
import AppCard5 from "./components/AppCard5";
import AppCardplat from "./components/AppCardplat.vue";

export default {
  name: "App",
  components: {
    Appheader,
    Appfooter,
    AppCard1,
    AppCard2,
    AppCard5,
    AppCard7,
    AppCard6,
    AppCardplat,
  },
  data() {
    return {
      cardData: [
        {
          id: "efyhuhsk",
          text: "Findtrend helps you to increase your productivity and reduce your computer's memory load ",
          description:
            " an application that can fulfill your daily browsing needs.",
          description1: "Findtrend make +1000 Startup grow",
          url: require("@/assets/image116.svg"),
          url: require("@/assets/image117.svg"),
          url: require("@/assets/image118.svg"),
          url: require("@/assets/image119.svg"),
          url: require("@/assets/image120.svg"),
          url: require("@/assets/image121.svg"),
          url: require("@/assets/image122.svg"),
          url: require("@/assets/image124.svg"),
          url: require("@/assets/image125.svg"),
          url: require("@/assets/image126.svg"),
          url: require("@/assets/image127.svg"),
          url: require("@/assets/image128.svg"),
          url: require("@/assets/image129.svg"),
          url: require("@/assets/image130.svg"),

          url: require("@/assets/image132.svg"),
          url: require("@/assets/image133.svg"),
          // url: require("@/assets/image116.svg"),
          // url: require("@/assets/image116.svg"),
          // url: require("@/assets/image116.svg"),
        },
      ],
    };
  },
};
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
h1 {
  text-align: center;
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
@font-face {
  font-family: "Effra";
  src: local("Effra"), url(./fonts/Effra_Std_Rg.ttf) format("truetype");
}
</style>
