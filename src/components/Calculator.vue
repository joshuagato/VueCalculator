<template>
  <div class="calculator">
    <div class="display">0.000154</div>
    <div class="button">C</div>
    <div class="button">+/-</div>
    <div class="button">%</div>
    <div class="button operator">÷</div>
    <div class="button">7</div>
    <div class="button">8</div>
    <div class="button">9</div>
    <div class="button operator">x</div>
    <div class="button">4</div>
    <div class="button">5</div>
    <div class="button">6</div>
    <div class="button operator">-</div>
    <div class="button">1</div>
    <div class="button">2</div>
    <div class="button">3</div>
    <div class="button operator">+</div>
    <div class="button zero">0</div>
    <div class="button">.</div>
    <div class="button operator">=</div>
  </div>
</template>

<script>
export default {
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  .calculator {
    width: 25rem;
    margin: 0 auto;
    font-size: 40px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-auto-rows: minmax(50px, auto);
  }

  .display {
    grid-column: 1 / 5;
    background-color: #383a3a;
    color: antiquewhite;
  }

  .zero {
    grid-column: 1 / 3;
  }

  .button {
    background-color: #eee;
    border: 1px solid #333;
  }

  .operator {
    background-color: #606c6d;
    color: white;
  }
  
</style>
