<template>
  <h1 class="trends">Findtrend make +1000 Startup grow</h1>
  <div id="flexid">
    <div id="flex2" v-for="card in cardData" :key="card.id">
      <img :src="card.url" alt="" />
    </div>
  </div>
</template>
<script>
export default {
  name: "AppCard5",
  data() {
    return {
      cardData: [
        {
          id: "efyhsk",
          url: require("@/assets/image116.svg"),
        },
        {
          id: "efyhesk",
          url: require("@/assets/image117.svg"),
        },
        {
          id: "efrfyhsk",

          url: require("@/assets/image118.svg"),
        },
        {
          id: "efyhsks",

          url: require("@/assets/image119.svg"),
        },
        {
          id: "ewfyhsk",

          url: require("@/assets/image120.svg"),
        },
        { id: "efyhskq", url: require("@/assets/image121.svg") },
        { id: "wdefyhsk", url: require("@/assets/image122.svg") },
        { id: "efyhskrd", url: require("@/assets/image124.svg") },
        {
          id: "efyhsker",

          url: require("@/assets/image125.svg"),
        },
        { id: "efyhskddf", url: require("@/assets/image126.svg") },
        { id: "efywqhsk", url: require("@/assets/image127.svg") },
        { id: "efqryhsk", url: require("@/assets/image128.svg") },
        { id: "ethfyhsk", url: require("@/assets/image129.svg") },
        { id: "efyhegbsk", url: require("@/assets/image130.svg") },
        { id: "qwefyhsk", url: require("@/assets/image132.svg") },
        { id: "poefyhsk", url: require("@/assets/image133.svg") },
      ],
    };
  },
};
</script>

<style scoped>
#flex2 {
  width: 266px;
  height: 120px;
  left: 736px;
  top: 2522px;
  background: #f5f5f5;
  border-radius: 8px;
}
#flexid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  text-align: center;
}
.trends {
  margin-top: 240px;
  margin-bottom: 60px;
  font-family: "Effra";
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  line-height: 76px;
  text-align: center;

  color: #000000;
}
</style>
