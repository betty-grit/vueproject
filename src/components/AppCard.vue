<template>
  <div class="maindiv">
    <img :src="cardUrl" alt="" />
    <h4>{{ cardText }}</h4>
    <p>{{ cardDescription }}</p>
    <h4>{{ cardDescription1 }}</h4>
  </div>
</template>
<script>
export default {
  name: "AppCard",
  props: ["cardUrl", "cardText", "cardDescription", "cardDescription1"],
};
</script>
<style>
.maindiv {
  display: inline-block;
}
</style>
