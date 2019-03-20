<template>
  <div class="calculator">
    <div class="display"></div>
    <dir class="btn">C</dir>
    <dir class="btn">+/-</dir>
    <dir class="btn">%</dir>
    <dir class="btn">÷</dir>
    <dir class="btn">7</dir>
    <dir class="btn">8</dir>
    <dir class="btn">9</dir>
    <dir class="btn">x</dir>
    <dir class="btn">4</dir>
    <dir class="btn">5</dir>
    <dir class="btn">6</dir>
    <dir class="btn">-</dir>
    <dir class="btn">1</dir>
    <dir class="btn">2</dir>
    <dir class="btn">3</dir>
    <dir class="btn">+</dir>
    <dir class="btn zero">0</dir>
    <dir class="btn">.</dir>
    <dir class="btn">=</dir>
  </div>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.calculator {
  margin: 0 auto;
  width: 400px;
  font-size: 30px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}
.display {
  grid-column: 1 / 5;
  background-color: chartreuse;
}
.zero {
  grid-column: 1 / 3;
}
.btn {
  margin: 0;
  background-color: #eee;
  border: 1px solid #333
}

</style>
