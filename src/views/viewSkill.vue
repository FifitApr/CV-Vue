<template>
  <div class="about">
    <h1>Kemampuan Saya</h1>
  </div>
  <p>HTML</p>
    <div class="container1">
        <div class="skills html">85%</div>
    </div>
  <p>CSS</p>
    <div class="container1">
        <div class="skills css">75%</div>
    </div>
  <p>FIGMA</p>
    <div class="container1">
        <div class="skills figma">87%</div>
    </div>
  <p>WORDPRESS</p>
    <div class="container1">
        <div class="skills wordpress">85%</div>
    </div>
  <p>MYSQL</p>
    <div class="container1">
        <div class="skills mysql">70%</div>
    </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    /* min-height: 100vh; */
    display: flex;
    align-items: center;
    margin-bottom: 20px;
  }
  .container1 {
    width: 100%;
    background-color: #ddd;
  }
  .skills {
    text-align: right;
    padding-top: 10px;
    padding-bottom: 10px;
    color: rgba(255, 255, 255, 0.938);
    
  }
  .html {
    width: 85%;
    background-color: #256D85;
  }
  .css{
    width: 75%;
    background-color: #2B4865;
  }
  .figma{
    width: 87%;
    background-color: #355764;
  }
  .wordpress{
    width: 85%;
    background-color: #003865;
  }
  .mysql{
    width: 75%;
    background-color: #425d64;
  }
}
</style>