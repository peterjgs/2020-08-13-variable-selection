---
title: "Variable selection"
author: "Peter Geelan-Small, Stats Central"
date: "13/08/2020"
output: 
  revealjs::revealjs_presentation:
    theme: simple
    center: false
    transition: none
    keep_md: true
    mathjax: default
    reveal_plugins: ["notes"]
    self_contained: false
    reveal_options:
      slideNumber: true
---


<style type="text/css">

.reveal p:first-child { 
  margin-top: 0px;    
}
.reveal .slides > section {
  padding: 0px; 
}
.reveal div.slides {
  position: absolute; top: -15%; 
}

.reveal {
	font-size: 30pt;
}

.reveal h1,
.reveal h2,
.reveal h3,
.reveal h4,
.reveal h5,
.reveal h6 {
  margin: $headingMargin;
  color: #963216;
}

.header {
  padding: 50px;
}

.reveal p {
  text-align: left;
}

.reveal ul {
  display: block;
}

.reveal ol {
  display: block;
}  

</style>





# Variable or model selection

Why are you modelling?

- looking at a focal predictor

- finding which predictors are _active_ predictors

- predicting value of response from predictors



