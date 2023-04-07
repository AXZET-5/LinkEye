<script setup>
defineProps({
})
</script>

<template>
  <img src="../assets/linkeye_logo.png" class="Inline Logo">
  <h1 class="Inline Name"> LinkEye</h1>
  <p class="Subtitle">V2.0.0<br><br>
    Welcome to LinkEye, a one-page view for all the links you need.<br>
  Created by Benz Chong 23S6H<br><br>
  You are viewing: 23S6H PCME</p>
</template>

<style>
  .Logo {
    width: 50px;
    display: inline;
    filter: saturate(4);
    filter: brightness(1.5);
  }
  .Inline {
    display: inline;
  }
  .Name {
    color: black;
    -webkit-text-stroke: 2px rgb(179,255,255);
    vertical-align: top;
    font-family: Segoe UI, AvenirNext-Regular, sans-serif;
    font-weight: 1000;
  }
  .Subtitle {
    color: rgb(230,255,255);
    font-family: Segoe UI, AvenirNext-Regular, sans-serif;
  }
</style>