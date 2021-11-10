<template>
  <div class="App">
    <h1>
      Web Components Cards
      <img
        src="@/assets/card.png"
        alt=""
        srcset=""
        style="height: 32px; width: 32px"
      />
    </h1>

    <img src="@/assets/vuejs-icon.svg" alt="" srcset="" />
    <search-result v-bind:name-attribute="name"></search-result>
  </div>
</template>

<script>
import "./web-components/search-result.js";
export default {
  data() {
    return {
      name: "",
    };
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Major+Mono+Display&family=Share+Tech+Mono&display=swap");
.App {
  margin-top: 30px;
  text-align: center;
}
.greeting {
  margin-top: 20px;
}
h1 {
  font-family: "Major Mono Display", monospace;
}
</style>
