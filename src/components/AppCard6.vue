<template>
  <div class="background">
    <h1>Get your best deal</h1>
    <div class="first">
      <p>Monthly</p>
      <img src="@/assets/Grouptoggle.svg" />
      <p>Yearly</p>
      <img src="@/assets/Groups1.svg" />
    </div>

    <div class="cardss">
      <div id="flex2" v-for="card in cardDeal" :key="card.id"></div>
      :key="card.id" :cardUrl="card.url" :cardTitle="card.title"
      :cardDescription="card.description"
    </div>
  </div>
</template>
<script>
export default {
  name: "AppCard6",
  data() {
    return {
      cardDeal: [
        {
          id: "erigkhj",
          text: "Personal",
          description: "Special first packet for all",
          price: "$8",
          month: "/Month",
          sect: [
            {
              id: "12",
              url: require("@/assets/Frame29.svg"),
              mark1: "Up to 5 page each group",
            },
            {
              id: "125",
              url: require("@/assets/Group97.svg"),
              mark2: "Up to 10 group page",
            },
            {
              id: "121",
              url: require("@/assets/Group97.svg"),
              mark3: "5 Days group page saved",
            },
          ],
        },
        {
          id: "erigtfkhj",
          text: "Regular",
          description: "Recommended for personal pro",
          price: "$20",
          month: "/Month",
          sect1: [
            {
              id: "134",
              url: require("@/assets/Group97.svg"),
              mark1: "Up to 15 page each group",
            },
            {
              id: "245",
              url: require("@/assets/Group97.svg"),
              mark2: "Download page up to 20 page",
            },
            {
              id: "289",
              url: require("@/assets/Group97.svg"),
              mark3: "Up to 10 group page",
            },
            {
              id: "216",
              url: require("@/assets/Group97.svg"),
              mark4: "15 Days group page saved",
            },
          ],
        },
        {
          id: "eredigkhj",
          text: "Premium",
          description: "Packet for Startup & Company",
          price: "$48",
          month: "/Month",
          sect3[
          {id:"780",url:require("@/assets/Group97.svg") , mark1: "Unlimited group pages"},
         {id:"269",url:require("@/assets/Group97.svg") , mark2: "Unlimited download page"},
          {id:"329",url:require("@/assets/Group97.svg") , mark3: "Unlimited page each group"},
          {id:"674",url:require("@/assets/Group97.svg") , mark4: "Customize sorting group pages"},
          {id:"5231",url:require("@/assets/Group97.svg") , mark5: "Customize group page name"},
          {id:"5132",url:require("@/assets/Group97.svg") , mark6: "30 Days group page saved"},
          ]
        },
      ],
    };
  },
};
</script>
<style scoped>
p {
  color: white;
}
.first {
  display: flex;
}
.background {
  background-color: black;
}
</style>
