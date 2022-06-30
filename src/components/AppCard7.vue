<template>
  <div class="container">
    <h1 class="join">Join us on email for</h1>
    <h2 class="trending">more trending topics</h2>
    <Appbutton class="joinus" text="join us" />
  </div>
</template>
<script>
import Appbutton from "@/components/Appbutton.vue";
export default {
  name: "AppCard7",
  components: { Appbutton },
};
</script>
<style>
.container {
  background-color: #a8ff35;
  padding-bottom: 140px;
}
.join {
  font-style: Heavy;
  font-size: 72px;
  padding-top: 140px;
}
.trending {
  font-style: Heavy;
  font-size: 72px;
  text-align: center;
  margin-bottom: 40px;
}
.joinus {
  width: 180px;
  height: 56px;
  padding: 16px, 32px, 16px, 32px;
  border-radius: 40px;
  background-color: black;
  color: white;
  border: none;
  align-items: center;
  display: block;
  margin-left: auto;
  margin-right: auto;
  cursor: pointer;
}
</style>
