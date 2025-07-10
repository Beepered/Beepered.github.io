<!--
Progress Bar
https://www.youtube.com/watch?v=-q8rtVK_Z04&t=558s&ab_channel=TylerPotts
-->

<template>
  <div class="progress_bar">
    <div class="progress_inner">
      <span>0%</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "progress_bar",

}
</script>

<style>
.progress_bar {
  width: 70%;
  height: 15%;
  background-color: #b4b4b4;
  position: relative;
}

.progress_inner {
  height: 100%;
  background-image: linear-gradient(to right, #0ccc76, #055632);
}
</style>