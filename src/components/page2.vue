<template>
  <div class="yellow-div">
    <p>
      Minimalist is a full-service digital creative agency located in Ontorio
      Canada. We focus on design, consulting, technology, and photography. We’ve
      been building unique digital products, platforms, and experiences for the
      past 6 years. Let us help your company grow.
    </p>
    <button>Get in Touch</button>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>

.yellow-div {
    // width: 100%;
    height: 289px;
    background-color: #fefec9;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    gap: 40px;
    padding: 0 300px;
}
.yellow-div p {
    color: #47474f;
    text-align: center;
    font-family: Vollkorn;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 25px;
}
.yellow-div button {
    width: 159px;
    height: 53px;
    flex-shrink: 0;
    background-color: #fefec9;
    color: #47474f;
    text-align: center;
    font-family: Vollkorn;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    border: 2px solid gray;
    line-height: 20px;
}


</style>