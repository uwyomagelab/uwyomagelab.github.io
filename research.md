---
layout: page
title: Research
subtitle: Current research projects
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
}

.flip-box {
  background-color: transparent;
  width: 300px;
  height: 200px;
  border: 1px solid #f1f1f1;
  perspective: 1000px;
  float: left;
  margin-right: 60px!important;
}

.flip-box-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

.flip-box:hover .flip-box-inner {
  transform: rotateY(180deg);
}

.flip-box-front, .flip-box-back {
  position: absolute;
  width: 100%;
  height: 101%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-box-front {
  background-color: #bbb;
  color: black;
  background-size: cover;
}

.flip-box-back {
  background-color: lightgrey;
  color: white;
  transform: rotateY(180deg);
  background-size: cover;
  justify-content: center;
}
</style>
</head>
<body>

<div class="flip-box">
  <div class="flip-box-inner">
    <div class="flip-box-front">
      <img src="hiv.png" style="width:300px, height:200px">
    </div>
    <div class="flip-box-back">
      <a href="https://aemann01.github.io/projects/hiv_oral_microbiome/"><p>The role of the human oral microbiome in health and disease</p></a>
    </div>
  </div>
</div>

<div class="flip-box">
  <div class="flip-box-inner">
    <div class="flip-box-front">
      <img src="dentcalc.png" style="width:300px, height:200px">
    </div>
    <div class="flip-box-back">
     <a href="https://aemann01.github.io/projects/arch_dental_calc/"><p>Preservation of biomolecules in archaeological dental calculus</p></a>
    </div>
  </div>
</div>

<div class="flip-box">
  <div class="flip-box-inner">
    <div class="flip-box-front">
      <img src="ads.png" style="width:300px, height:200px">
    </div>
    <div class="flip-box-back">
      <a href="https://aemann01.github.io/projects/metatranscriptomics/"><p>Microbial metatranscriptomics</p></a>
    </div>
  </div>
</div>

<div class="flip-box">
  <div class="flip-box-inner">
    <div class="flip-box-front">
      <img src="primate_map.png" style="width:300px, height:200px">
    </div>
    <div class="flip-box-back">
      <a href="https://aemann01.github.io/projects/gut_euks/"><p>Evolution of the hominin gut microbiome</p></a>
    </div>
  </div>
</div>


</body>
</html>

