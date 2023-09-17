<template>
  <div>
    <div class="projects">
      <h2 id="projects" class="rec">Recent projects</h2>
      <hr />
      <div class="projects-item">
        <div>
          <img src="../assets/p.png" alt="" />
          <h2 class="projects-h2">woods</h2>
          <p>Photography</p>
        </div>

        <div>
          <img src="../assets/p2.png" alt="" />
          <h2 class="projects-h2">path</h2>
          <p>Website • Photography</p>
        </div>

        <div>
          <img src="../assets/p3.png" alt="" />
          <h2 class="projects-h2">darkness</h2>
          <p>Website</p>
        </div>
      </div>

      <div class="projects-item">
        <div>
          <img src="../assets/p4.png" alt="" />
          <h2 class="projects-h2">waves</h2>
          <p>Photography</p>
        </div>

        <div>
          <img src="../assets/p5.png" alt="" />
          <h2 class="projects-h2">drops</h2>
          <p>Website</p>
        </div>

        <div>
          <img src="../assets/p6.png" alt="" />
          <h2 class="projects-h2">ocean</h2>
          <p>Website</p>
        </div>
      </div>

      <div class="projects-item">
        <div>
          <img src="../assets/p7.png" alt="" />
          <h2 class="projects-h2">town</h2>
          <p>Website</p>
        </div>

        <div>
          <img src="../assets/p8.png" alt="" />
          <h2 class="projects-h2">mountain</h2>
          <p>Website</p>
        </div>

        <div>
          <img src="../assets/p9.png" alt="" />
          <h2 class="projects-h2">camera</h2>
          <p>Website</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.projects {
  display: flex;
  width: 100%;
  height: 1469px;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background: #f5f5f5;
  gap: 20px;
}

.rec {
  color: #333;
  text-align: center;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-size: 23px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px; /* 156.522% */
  text-transform: uppercase;
}

.projects hr {
  width: 80px;
  height: 2px;
  color: rgb(172, 172, 172);
  margin-top: 28px;
  margin-bottom: 43px;
}

.projects-item {
  display: flex;
  width: 100%;
  align-items: center;
  justify-content: center;
  flex-direction: row;
  gap: 20px;
}

.projects-item div {
  background-color: white;
  display: flex;
  align-items: center;
  /* justify-content: center; */
  flex-direction: column;
  width: 20%;
  height: 384px;
}

.projects-h2 {
  color: #333;
  text-align: center;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px; /* 156.522% */
  text-transform: uppercase;
}
</style>