<script setup>
defineProps({
})
</script>

<template>
  <h1 class="Week">Odd Week</h1>
  <img class="Table" src="../assets/2024t1o.jpeg">
  <br><br>
  <h1 class="Week">Even Week</h1>
  <img class="Table" src="../assets/2024t1e.jpeg">
</template>

<style>
  .Week {
    color: black;
    -webkit-text-stroke: 1px rgb(200,255,255);
    vertical-align: top;
    font-family: Segoe UI, AvenirNext-Regular, sans-serif;
    font-weight: 1000;
    font-size: 30px;
  }
  .Table {
    width: 100%;
    padding: 0px;
    margin: 0px;
    border-radius: 20px;
  }
</style>