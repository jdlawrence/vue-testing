<template>
  <div class="JamilBase">
    Welcome to my page!
    <img
      class="JamilBase__turtles"
      src="./Teenage-mutant-ninja-turtles.jpg"
    >
    <div class="JamilBase__dummy-div"></div>
  </div>
</template>

<script>
export default {
  name: 'JamilBase',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">

.JamilBase {
  color: blue;
  font-size: 23px;

  &__turtles {
    width: 200px;
  }

  &__dummy-div {
    // background-color: red;
    height: 150px;
    width: 700px;
    // background: url("./bokeh.jpg") repeat center;
    background: url("./mario.svg") repeat center;
  }
}
</style>

