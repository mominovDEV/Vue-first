<template>
  <div>
    <header>
      <div class="logos">
        <img src="../assets/IMAGE1.jpg" alt="Minimal" />
        <h3 class="text-logo">MINIMAL</h3>
      </div>
      <ul>
        <li><a href="#procces">process</a></li>
        <li><a href="#projects">projects</a></li>
        <li><a href="#team">team</a></li>
        <li><a href="#contact">contact</a></li>
      </ul>
    </header>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
header {
  display: flex;
  align-items: center;
  justify-content: space-around;
  height: 106px;
  width: 100%;
  gap: 50px;
}

.logos {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  /* margin-right: 427px; */
}
img {
  width: 65px;
  height: 70px;
  flex-shrink: 0;
  overflow-clip-margin: content-box;
  overflow: clip;
}

.text-logo {
  margin-left: 18px;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  color: #333;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 38px; /* 172.727% */
  text-transform: uppercase;
  text-align: center;
}

ul {
  text-transform: uppercase;
  list-style-type: none;
  margin: 0;
  padding: 0;
  color: #585858;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 166.667% */
  text-transform: uppercase;
}

li {
  display: inline;
  margin-right: 34px;
  color: #5d5d5d;
}

li a {
  color: #5d5d5d;
  text-decoration: none;
}
</style>