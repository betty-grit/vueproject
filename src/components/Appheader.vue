<template>
  <div class="maincontainer">
    <header>
      <div class="tagname">
        <img src="@/assets/Logo(7).svg" />
        <h3>Findtrend</h3>
      </div>
      <nav>
        <ul>
          <li>About Us</li>
          <li>How it work</li>
          <li>Pricing</li>
          <li>Solution</li>
          <li>Features</li>
        </ul>
      </nav>
      <a href="">Login</a>
      <Appbutton class="regist" text="Register" />
    </header>
    <h1>Minimize your tabs.</h1>
    <h1>Find the trends!</h1>

    <div class="ptags">
      <p>
        Don’t let your computer memories consumes all of those browser tabs.
      </p>
      <p>
        Findtrend let you gathers all of your favorite website into one place.
      </p>
    </div>
    <Appbutton class="started" text="Get Started 🔥" />
    <img class="start" src="@/assets/img-hero.svg" />
    <div class="maindiv">
      <!-- <AppheadingImg
        v-for="images in cardsImage"
        :key="images.id"
        :imagesUrl="images.url"
      /> -->
      <img class="imagess" src="@/assets/btn-hero-socmed.svg" />
    </div>
  </div>
</template>

<script>
import Appbutton from "@/components/Appbutton.vue";
import AppheadingImg from "@/components/AppheadingImg.vue";
export default {
  name: "Appheader",
  components: { Appbutton, AppheadingImg },
  data() {
    return {
      cardsImage: [
        {
          id: "ouifig",
          url: require("@/assets/Group7.svg"),
        },
        {
          id: "ouesifig",
          url: require("@/assets/Group8.svg"),
        },
        {
          id: "ourfifig",
          url: require("@/assets/Group9.svg"),
        },
        {
          id: "ourrfifig",
          url: require("@/assets/Group10.svg"),
        },
      ],
    };
  },
};
</script>
<style scoped>
ul {
  margin-left: 240px;
  margin-top: 6px;
  display: flex;
  gap: 50px;
  text-decoration: none;
  color: #ffffff;
  list-style: none;
}
.maincontainer {
  background-image: url("@/assets/Bg-hero.svg");
}
header {
  display: flex;
  align-items: center;
  margin-bottom: 100px;
}
h1 {
  font-size: 72px;
  font-style: Heavy;
  line-height: 81px;
  display: block;
  text-align: center;
  margin-right: 0px;
  color: white;
}
p {
  font-size: 18px;
  font-style: Regular;
  color: #8b8b8b;
  line-height: 27px;
  align-items: center;
  text-align: center;
}
.ptags {
  margin-top: 24px;
}
.regist {
  border-radius: 40px;
  width: 130px;
  height: 42px;
}
a {
  font-size: 18px;
  margin-left: 120px;
  margin-right: 40px;
  text-decoration: none;
  color: white;
}
.started {
  width: 180px;
  height: 58px;
  background-color: #a8ff35;
  border-radius: 40px;
  margin-top: 40px;
  border: none;
  align-items: center;
  display: block;
  margin-left: auto;
  margin-right: auto;
  cursor: pointer;
}
.start {
  margin-top: 40px;
  border: none;
  align-items: center;
  display: block;
  margin-left: 790px;
  margin-top: -70px;
  margin-right: auto;
  cursor: pointer;
}
.maindiv {
  display: flex;

  align-items: center;
  justify-content: center;
}
.imagess {
  border: none;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
  cursor: pointer;
}
</style>
