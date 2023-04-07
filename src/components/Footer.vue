<script>
</script>

<template>
  <div class="Footer">

    <div class="NormalFooter">
      <img src="../assets/ctj_logo.png" class="Inline Logo">
      <text class="Bold Affiliation"> CTJ</text>
      <p class="Bold Content">© 2023 Benz Chong</p>
  
      <br>
      
      <p class="Content">Pictures by <u>Hwa Chong Institution</u></p>
      <p class="Content">Hosting by <u>Vercel</u></p>
      <p class="Content">This webste is not related to any institution or organisation in any way.</p>
    </div>

    <br><br>
    
    <div class="ColumnFooter">
      <div style="padding-right: 20px">
      <p class="Bold ColumnHeader">Errors</p>
      <p class="Content">Please contact me should there be any errors.</p>
      </div>
      <div>
      <p class="Bold ColumnHeader">Contact</p>
      <p class="Content">Email - 191214N</p>
      </div>
    </div>
  </div>
</template>

<style>
  .Footer {
    background-color: black;
    padding-top: 35px;
    padding-bottom: 35px;
  }

  .NormalFooter {
    width: 80%;
    margin-left: auto;
    margin-right: auto;
  }

  .ColumnFooter {
    display: grid;
    grid-template-columns: 1fr 1fr;
    width: 80%;
    margin-left: auto;
    margin-right: auto;
  }

  .Affiliation {
    color: white;
    font-family: Segoe UI, AvenirNext-Regular, sans-serif;
    font-size: 30px;
    vertical-align: top;
  }

  .ColumnHeader {
    color: white;
    font-family: Segoe UI, AvenirNext-Regular, sans-serif;
    font-size: 20px;
  }
  
  .Content {
    color: white;
    font-family: Segoe UI, AvenirNext-Regular, sans-serif;
    padding-bottom: 5px;
  }

  .Center {
    text-align: center;
  }

  .Bold {
    font-weight: 600;
  }
</style>