<script setup>
defineProps({
  
})
</script>

<template>
  <p class="BigTitle">Mass Communication</p>
  <br>
  
  <div class="GridContainer">
    <div class="GridChild">
      <p class="Subject">Portals</p>
      <br>
      <a class="Link" href="https://iemb.hci.edu.sg" target="_blank">iEMB</a><br><br>
      <a class="Link" href="https://isp.hci.edu.sg" target="_blank">ISP College</a><br><br>
      <a class="Link" href="https://isphs.hci.edu.sg" target="_blank">ISP HS</a>
    </div>
    <div class="GridChild">
      <p class="Subject">Cohort GClass</p>
      <br>
      <a class="Link" href="https://classroom.google.com/u/0/c/NTYxODEyMDk3OTI1" target="_blank">Physics</a><br><br>
      <a class="Link" href="https://classroom.google.com/u/0/c/NTQyMzQ0MDU5MTc5" target="_blank">Chemistry</a><br><br>
      <a class="Link" href="https://classroom.google.com/u/0/c/NTEyODIxMTY4MDA1" target="_blank">Economics</a><br><br>
      <a class="Link" href="https://classroom.google.com/u/0/c/NTE2NDk0MjU3NzQ5" target="_blank">SMTP-GATE</a>
    </div>
    <div class="GridChild">
      <p class="Subject">23S6H GClass</p>
      <br>
      <a class="Link" href="https://classroom.google.com/u/0/c/NTE2MDgyMTg1ODc4" target="_blank">Physics</a><br><br>
      <a class="Link" href="https://classroom.google.com/u/0/c/NTE2MTc2NjY0OTEx" target="_blank">Chemistry/CT</a><br><br>
      <a class="Link" href="https://classroom.google.com/u/0/c/NTkzODAxOTQzNzg1" target="_blank">Mathematics</a><br><br>
      <a class="Link" href="https://classroom.google.com/u/0/c/NTE2MDE3MDA3NjQ4" target="_blank">General Paper</a><br><br>
      <a class="Link" href="https://classroom.google.com/u/0/c/NTk0MTM3MzYzNjEw" target="_blank">Project Work</a>
    </div>
  </div>

  <br>
  <p class="BigTitle">Individual Subjects</p>
  <br>
  
  <div class="GridContainer">
    <div class="GridChild">
      <p class="Subject">Physics</p>
      <br>
      <a class="Link" href="https://drive.google.com/drive/folders/1XKX3KYUpEtjOn6Y45AYWt3ILBeIwTdmj" target="_blank">Google Drive</a><br><br>
      <a class="Link" href="https://sites.google.com/hci.edu.sg/hci-h2-physics-9749/home?pli=1&authuser=1" target="_blank">Google Sites</a><br><br>
      <a class="Link" href="https://mylabmastering.pearson.com/?courseId=11944599&key=1579114589204027960332023#/" target="_blank">Pearson Platform</a><br><br>
      <a class="Link" href="https://docs.google.com/document/d/16ki__UtQjypPnAqan-2f9buIx6L3ZilF/edit" target="_blank">Schedule</a>
    </div>
    <div class="GridChild">
      <p class="Subject">Chemistry</p>
      <br>
      <a class="Link" href="https://sites.google.com/hci.edu.sg/h2chem2324/" target="_blank">Google Sites</a><br><br>
      <a class="Link" href="https://ptable.com/?lang=en#Properties" target="_blank">Periodic Table</a><br><br>
      <a class="Link" href="https://sciencenotes.org/list-of-electron-configurations-of-elements/" target="_blank">SPDF Notation</a><br><br>
      <a class="Link" href="https://calendar.google.com/calendar/u/0/embed?src=c_f42h2bldr22vm53v1f24aeccs4@group.calendar.google.com&ctz=Asia/Singapore" target="_blank">Schedule</a><br><br>
      <a class="Link" href="https://www.alevelh2chemistry.com/wp-content/uploads/2019/05/9729-Data-Booklet-for-JC-A-Level-H1-H2-H3-Chemistry-Syllabuses-Original.pdf" target="_blank">Data Booklet</a>
    </div>
    <div class="GridChild">
      <p class="Subject">Mathematics</p>
      <br>
      <a class="Link" href="https://tinyurl.com/23-24-h2math" target="_blank">Google Sites</a><br><br>
      <a class="Link" href="https://drive.google.com/file/d/1VNASUKcdQWvBC8dXr527rr9h274W2UE2/view" target="_blank">Schedule</a><br><br>
      <a class="Link" href="https://www.seab.gov.sg/content/syllabus/alevel/2017Syllabus/ListMF26.pdf" target="_blank">List MF26</a>
    </div>
    <div class="GridChild">
      <p class="Subject">Economics</p>
      <br>
      <a class="Link" href="https://sites.google.com/hci.edu.sg/h2-econs-hub/home" target="_blank">Google Sites</a><br><br>
      <a class="Link" href="https://drive.google.com/drive/folders/1aRqqBIlqLxMrn_qSCGlUtq0zBMUFth_1" target="_blank">Panda Resources</a>
    </div>
    <div class="GridChild">
      <p class="Subject">General Paper</p>
      <br>
      <a class="Link" href="https://sites.google.com/hci.edu.sg/2023-c1-microsites/microsites" target="_blank">Google Sites</a>
    </div>
    <div class="GridChild">
      <p class="Subject">Project Work</p>
      <br>
      <a class="Link" href="https://sites.google.com/hci.edu.sg/hciprojectwork/home?authuser=0" target="_blank">Google Sites</a>
    </div>
  </div>
</template>

<style>
  .BigTitle {
    color: black;
    -webkit-text-stroke: 1px rgb(200,255,255);
    vertical-align: top;
    font-family: Segoe UI, AvenirNext-Regular, sans-serif;
    font-weight: 1000;
    font-size: 30px;
  }
  
  .GridContainer {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1rem;
  }

  .GridChild {
    background-color: rgb(30,30,30);
    border-radius: 30px;
    padding: 20px;
    color: white;
    font-family: Segoe UI, AvenirNext-Regular, sans-serif;
  }

  .Subject {
    color: white;
    font-size: 20px;
    font-weight: 500;
  }

  .Link {
    color: white;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 15px;
    padding-right: 15px;
    border: 2px solid rgb(200,200,200);
    border-radius: 30px;
    text-decoration: none;

    transition-duration: 0.3s;
  }

  .Link:hover {
    background-color: black;
    color: rgb(179,255,255);
    border: 2px solid rgb(179,255,255);
    padding-left: 25px;
    padding-right: 25px;
  }

  @media only screen and (min-width: 550px) {
    .GridContainer {
      grid-template-columns: 1fr 1fr;
    }
  }
  
  @media only screen and (min-width: 850px) {
    .GridContainer {
      grid-template-columns: 1fr 1fr 1fr;
    }
  }

  @media only screen and (min-width: 1150px) {
    .GridContainer {
      grid-template-columns: 1fr 1fr 1fr 1fr;
    }
  }
</style>
