<template>
  <div class="maindiv1">
    <div class="maindiv">
      <h4>Open new tabs is sh*t</h4>
      <div class="mindiv">
        <img src="@/assets/Group21.svg" alt="" />
        <div class="framsdiv1">
          <div class="framediv">
            <img class="frame" src="@/assets/Frame1.svg" alt="" />
          </div>
        </div>
        <img src="@/assets/Group22.svg" alt="" />
      </div>
      <p>
        "A solution for your browser tabs and don’t make your device get slower
        over time. Get
      </p>
      <p>ease and faster to discover a trend with just one tab."</p>
    </div>
  </div>
</template>
<script>
// import AppCard1 from "@/components/AppCard1.vue";
export default {
  name: "AppCard1",
  components: {},
};
</script>

<style scoped>
h4 {
  font-style: Bold;
  font-size: 72px;
  align-items: center;
  text-align: center;
  margin-top: 140px;
  margin-bottom: 60px;
}
p {
  font-style: Regular;
  font-size: 18px;
}
.maindiv {
  display: inline-block;
  align-items: center;
  display: block;
  margin-left: auto;
  margin-right: auto;
  cursor: pointer;
  text-align: center;
}
.maindiv1 {
  width: 1440px;
  height: 742px;
  background-color: #a8ff35;
}

.framsdiv1 {
  background-color: white;
  width: 502px;
  height: 202px;
  border-radius: 16px;
  margin-bottom: 60px;
}
.mindiv {
  display: flex;
}
.framediv {
  background-color: black;
  height: 82px;
  width: 340px;
}
.frame {
  align-items: center;
  text-align: center;
}
</style>
