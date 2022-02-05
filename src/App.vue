<template>
  <div id="app">
    <div class="col-1">
      <circleShimmer size="40px" />
    </div>
    <div class="col-2">
      <h1>
        <textShimmer />
      </h1>
      <small>
        <textShimmer />
      </small>
      <p>
        <sentencesShimmer lines="6" />
      </p>
    </div>
    <blockShimmer height="50px" width="60px" />
    <imageShimmer height="50" width="60" />
  </div>
</template>

<script>
import {
  blockShimmer,
  circleShimmer,
  imageShimmer,
  sentencesShimmer,
  textShimmer,
} from "shimmer";

export default {
  name: "App",

  components: {
    blockShimmer,
    circleShimmer,
    imageShimmer,
    sentencesShimmer,
    textShimmer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
