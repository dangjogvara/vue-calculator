<template>
  <div class="calculator">
    <div class="display">0.34454555</div>
    <span>Hello</span>
    <span>Hello</span>
    <span>Hello</span>
    <span>Hello</span>
    <span>Hello</span>
    <span>Hello</span>
    <span>Hello</span>
    <span>Hello</span>
    <span>Hello</span>
    <span>Hello</span>
    <span>Hello</span>
  </div>
</template>

<script>
  export default {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .calculator {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-auto-rows: minmax(50px, auto);
  }

  .display {
    grid-column: 1 / 5;
  }
</style>
