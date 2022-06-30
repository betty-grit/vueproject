<template>
  <footer>
    <img src="@/assets/Vector(16).svg" />
    <p>Findtrend</p>
    <nav>
      <ul>
        <li>Privacy Policy</li>
        <li>Terms and Conditions</li>
        <li>Contact Us</li>
        <li>Careers</li>
      </ul>
    </nav>
  </footer>
</template>
<script>
export default {
  name: "Appfooter",
};
</script>
<style scoped>
img {
  margin-left: 20px;
  margin-right: 5px;
}
p {
  margin-right: 450px;
}
ul {
  margin-left: 240px;
  margin-top: 6px;
  display: flex;
  gap: 50px;
  text-decoration: none;
  color: black;
  list-style: none;
  text-align: center;
}
footer {
  display: flex;
}
</style>
