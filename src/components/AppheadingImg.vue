<template>
  <div class="maindiv">
    <img :src="imagesUrl" alt="" />
  </div>
</template>
<script>
export default {
  name: "AppheadingImg",
  props: ["imagesUrl"],
};
</script>
<style>
.maindiv {
  display: flex;
}
</style>
