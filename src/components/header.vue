<template>
  <div class="header">
    <h3 class="title1">Making brands stand out</h3>
    <h3 class="title1 tit">is our obsession</h3>
    <hr />
    <p>Let us help your brand stand out.</p>
  </div>
</template>
<script>
export default {};
</script>

<style lang="scss" scoped>
.header {
  width: 100%;
  height: 391px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  background-image: url("../assets/IMAGE2.jpg");
  background-size: cover;
}
.title1 {
  color: #fff;
  text-align: center;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-size: 44px;
  font-style: normal;
  font-weight: 400;
  line-height: 55px;
  text-transform: uppercase;
}
// .tit {
//     margin-bottom: 28px;
// }
hr {
  width: 80px;
  height: 2px;
  color: gray;
  background-color: #fff;
}
p {
  color: rgba(255, 255, 255, 0.81);
  text-align: center;
  font-family: Vollkorn;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 133.333% */
}
</style>