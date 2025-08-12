---
title: ""
aliases: /code/
description: "R packages, APIs, and computational tools for economics research and data analysis."
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
button.accordion {
font:14px/1.5 Lato, "Helvetica Neue", Helvetica, Arial, sans-serif;
cursor: pointer;
padding: 0px;
border: none;
text-align: left;
outline: none;
font-size: 100%;
transition: 0.3s;
background-color: #f8f8f8;
}

button.accordion.active, button.accordion:hover {
background-color: #f8f8f8;
}

button.accordion:after {
content: " [+] ";
font-size: 90%;
color:#777;
float: left;
margin-left: 1px;
}

button.accordion.active:after {
content: " [\2212] ";
}

div.panel {
padding: 0 20px;
margin-top: 5px;
display: none;
background-color: white;
font-size: 100%;
}

div.panel.show {
display: block !important;
}

.link-item {
margin-bottom: 8px;
}

.link-label {
font-weight: bold;
color: #1976d2;
}

.section-heading {
font-size: 120%;
font-weight: bold;
color: #333;
margin-top: 20px;
margin-bottom: 15px;
border-bottom: 2px solid #1976d2;
padding-bottom: 5px;
}

.note-box {
background-color: #e3f2fd;
border: 1px solid #1976d2;
border-radius: 5px;
padding: 15px;
margin: 20px 0;
font-style: italic;
}
</style>

<div class="section-heading">R Packages and Data APIs</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">rscorecard</a> <br>
<i>R Wrapper for the U.S. Department of Education College Scorecard API</i> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The rscorecard package is an R wrapper for the U.S. Department of Education College Scorecard API. It allows users to select and filter Scorecard variables with piped commands using dplyr syntax, making it easy to access comprehensive college and university data for higher education research.</p>
</div>

<p style="margin:0">
<button class="accordion">Links</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<div class="link-item"><span class="link-label">GitHub Repository:</span> <a href="https://github.com/btskinner/rscorecard" target="_blank">btskinner/rscorecard</a></div>
</div>

<br>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">econocharts</a> <br>
<i>Microeconomics and Macroeconomics Charts Made with ggplot2</i> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The econocharts package allows creating microeconomics or macroeconomics charts in R with simple functions. This package is inspired by reconPlots by Andrew Heiss and provides an easy way to generate professional economic visualizations including supply and demand curves, indifference curves, production possibility frontiers, and tax impact analysis.</p>
</div>

<p style="margin:0">
<button class="accordion">Links</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<div class="link-item"><span class="link-label">GitHub Repository:</span> <a href="https://github.com/ahmedelfatmaoui/econocharts" target="_blank">ahmedelfatmaoui/econocharts</a></div>
</div>

<br>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">blsAPI</a> <br>
<i>U.S. Bureau of Labor Statistics Data for R</i> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The blsAPI package allows R users to request data for one or multiple series through the U.S. Bureau of Labor Statistics (BLS) Application Programming Interface (API). The BLS API provides public access to economic data from all BLS programs including employment, unemployment, and labor market statistics.</p>
</div>

<p style="margin:0">
<button class="accordion">Links</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<div class="link-item"><span class="link-label">GitHub Repository:</span> <a href="https://github.com/ahmedelfatmaoui/blsAPI" target="_blank">ahmedelfatmaoui/blsAPI</a></div>
</div>

<br>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">bea.R</a> <br>
<i>Bureau of Economic Analysis API Access for R</i> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The bea.R package provides programmatic access to U.S. Bureau of Economic Analysis data through their API. This package enables researchers to easily retrieve and analyze national and regional economic statistics including GDP, national accounts, and comprehensive economic indicators.</p>
</div>

<p style="margin:0">
<button class="accordion">Links</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<div class="link-item"><span class="link-label">GitHub Repository:</span> <a href="https://github.com/ahmedelfatmaoui/bea.R" target="_blank">ahmedelfatmaoui/bea.R</a></div>
</div>

<br>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">urbnmapr</a> <br>
<i>State and County Maps with Alaska and Hawaii</i> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The urbnmapr package provides state and county maps for the United States with Alaska and Hawaii repositioned for better visualization. This package makes it easy to create appealing and informative choropleth maps with pre-formatted spatial data optimized for data visualization.</p>
</div>

<p style="margin:0">
<button class="accordion">Links</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<div class="link-item"><span class="link-label">GitHub Repository:</span> <a href="https://github.com/ahmedelfatmaoui/urbnmapr" target="_blank">ahmedelfatmaoui/urbnmapr</a></div>
</div>

<br>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">education-data-package-r</a> <br>
<i>Urban Institute Education Data Portal API for R</i> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The education-data-package-r provides R users with access to the Urban Institute's Education Data Portal API, containing comprehensive U.S. education datasets. Essential for education researchers, policy analysts, and anyone studying trends in American education systems.</p>
</div>

<p style="margin:0">
<button class="accordion">Links</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<div class="link-item"><span class="link-label">GitHub Repository:</span> <a href="https://github.com/ahmedelfatmaoui/education-data-package-r" target="_blank">ahmedelfatmaoui/education-data-package-r</a></div>
</div>

<br>

<div class="note-box">
<strong>Note:</strong> For additional computational tools and codes in Julia, Matlab, and LaTeX, visit <a href="https://tyleransom.github.io/code.html" target="_blank">Tyler Ransom's code page</a>, which contains a wealth of interesting programming resources for economics research.
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
    acc[i].onclick = function(){
        this.classList.toggle("active");
        this.parentNode.nextElementSibling.classList.toggle("show");
    }
}
</script>

<!-- Default Statcounter code for Personal Website
https://ahmedelfatmaoui.github.io/ -->
<script type="text/javascript">
var sc_project=12988052; 
var sc_invisible=1; 
var sc_security="0346b3d7"; 
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js" async></script>
<noscript><div class="statcounter"><a title="Web Analytics"
href="https://statcounter.com/" target="_blank"><img class="statcounter"
src="https://c.statcounter.com/12988052/0/0346b3d7/1/" alt="Web Analytics"
referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>
<!-- End of Statcounter Code -->