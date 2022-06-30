<template>
  <div class="section2">
    <h1 class="platss">All platform connect to Findtrend</h1>
    <div class="flexe2" v-for="cards in imageData" :key="cards.id">
      <img :src="cards.url" alt="" />
    </div>
  </div>
  <div class="tweets">
    <img src="@/assets/tweet1.svg" alt="" />
    <img src="@/assets/tweet2.svg" alt="" />
    <img src="@/assets/tweet3.svg" alt="" />
  </div>
  <Appbutton class="tweetbutton" text="View More Trend"></Appbutton>
</template>
<script>
import Appbutton from "@/components/Appbutton.vue";
export default {
  name: "AppCardplat",
  components: { Appbutton },
  data() {
    return {
      imageData: [
        {
          id: "efyhskh",
          url: require("@/assets/Group33(1).svg"),
        },
        {
          id: "efyhetsk",
          url: require("@/assets/Group34.svg"),
        },
        {
          id: "efrfyhsyk",

          url: require("@/assets/Group35.svg"),
        },
        {
          id: "efyhskngs",

          url: require("@/assets/Group36.svg"),
        },
        {
          id: "ewfyhiosk",

          url: require("@/assets/Group37.svg"),
        },
        { id: "efyhskrtq", url: require("@/assets/Group38.svg") },
        { id: "wdefyhpnsk", url: require("@/assets/Group39(1).svg") },
        { id: "efyhsuikrd", url: require("@/assets/Group40.svg") },
      ],
    };
  },
};
</script>
<style scoped>
.platss {
  color: black;
  margin-top: 140px;
  text-align: center;
}
.flexe2 {
  display: inline-block;
  text-align: center;
}
.section2 {
  width: 1440px;
  text-align: center;
  background-color: #fafafa;
}
.tweets {
  margin-top: 30px;
  text-align: center;
}
.tweetbutton {
  width: 198px;
  height: 57px;
  background: #000000;
  border-radius: 40px;
  color: white;
  align-items: center;
  display: block;
  margin-left: auto;
  margin-right: auto;
  cursor: pointer;
}
</style>
