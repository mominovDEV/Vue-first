<template>
  <div>
    <h2 id="procces" class="wrapper-h2">How we make brands thrive</h2>
    <hr/>
    <div class="how">
      <div class="hows-item">
        <div class="hows-div"><img src="../assets/page3-1.png" alt="" /></div>
        <h3>SET a target</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
          varius enim in eros elementum tristique.
        </p>
      </div>

      <div class="hows-item">
        <div class="hows-div"><img src="../assets/page3-2.png" alt="" /></div>
        <h3>design a solution</h3>
        <p>
          Duis cursus, mi quis viverra ornare, eros &nbsp; &nbsp; &nbsp; &nbsp;
          dolor interdum nulla, ut commodo diam &nbsp; &nbsp; &nbsp; &nbsp;
          libero vitae erat.
        </p>
      </div>

      <div class="hows-item">
        <div class="hows-div"><img src="../assets/page3-3.png" alt="" /></div>
        <h3>track the progress</h3>
        <p>
          Aenean faucibus nibh et justo cursus id&nbsp;rutrum lorem imperdiet.
          Nunc ut sem vitae risus tristique posuere.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.how {
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    gap: 20px;
}
.hows-item {
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    width: 20%;
}
.hows-div {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background: #f5f5f5;
    width: 100%;
    height: 219px;
    margin-bottom: 38px;
}

.hows-item h3 {
    color: #333;
    text-align: center;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    text-transform: uppercase;
    margin-bottom: 20px;
}
hr {
    width: 80px;
    height: 2px;
    color: rgb(255, 255, 255);
    margin-top: 28px;
    background-color: #fff;
    margin-bottom: 43px;
}

.hows-item p {
    text-align: center;
    color: #333;
    text-align: center;
    font-family: Vollkorn;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 22px;
    margin-bottom: 74px;
}



</style>