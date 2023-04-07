<script setup>
import Heading from "./components/Heading.vue"
import GridContainer from "./components/GridContainer.vue"
import Timetable from "./components/Timetable.vue"
import Footer from "./components/Footer.vue"
</script>

<template>
  <header></header>
  
  <main>
    <div class="Wrapper">
      <Heading></Heading>
    </div>
    
    <div class="Wrapper">
      <GridContainer></GridContainer>
    </div>

    <div class="Wrapper">
      <Timetable></Timetable>
    </div>

    <Footer></Footer>
  </main>
</template>

<style>
.Wrapper {
  background-color: black;
  padding: 25px;
  border-radius: 30px;
  box-shadow: 0px 0px 5px 5px rgb(179,255,255);
  width: 80%;
  margin-left: auto;
  margin-right: auto;
  margin-top: 30px;
  margin-bottom: 30px;
  display: block;
} 

* {
  padding: 0;
  margin: 0;
}
</style>
