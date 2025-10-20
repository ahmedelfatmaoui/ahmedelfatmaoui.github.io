---
title: ""
aliases: /code/
description: "R packages, APIs, computational tools, and educational resources for economics research and data analysis."
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

<div style="
  background-color: #1976d2;
  color: white;
  text-align: center;
  padding: 12px 0;
  font-size: 110%;
  font-weight: bold;
  border-radius: 6px;
  margin-bottom: 20px;
">
  🔒 Access Restricted—ECO 230 Students Only  
  <br>
  <a href="https://posit.cloud/spaces/695951/content/10960883" target="_blank" style="
    color: white;
    text-decoration: underline;
  ">
    Open Lab – Statistics in the Tidyverse (Part 1)
  </a>
</div>



<div class="section-heading">R Packages and Data APIs</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">rscorecard</a> <br>
<i>R Wrapper for the U.S. Department of Education College Scorecard API</i> <br>
<strong>GitHub Repository:</strong> <a href="https://github.com/btskinner/rscorecard" target="_blank">btskinner/rscorecard</a> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The rscorecard package is an R wrapper for the U.S. Department of Education College Scorecard API. It allows users to select and filter Scorecard variables with piped commands using dplyr syntax, making it easy to access comprehensive college and university data for higher education research.</p>
</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">econocharts</a> <br>
<i>Microeconomics and Macroeconomics Charts Made with ggplot2</i> <br>
<strong>GitHub Repository:</strong> <a href="https://github.com/ahmedelfatmaoui/econocharts" target="_blank">ahmedelfatmaoui/econocharts</a> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The econocharts package allows creating microeconomics or macroeconomics charts in R with simple functions. This package is inspired by reconPlots by Andrew Heiss and provides an easy way to generate professional economic visualizations including supply and demand curves, indifference curves, production possibility frontiers, and tax impact analysis.</p>
</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">blsAPI</a> <br>
<i>U.S. Bureau of Labor Statistics Data for R</i> <br>
<strong>GitHub Repository:</strong> <a href="https://github.com/ahmedelfatmaoui/blsAPI" target="_blank">ahmedelfatmaoui/blsAPI</a> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The blsAPI package allows R users to request data for one or multiple series through the U.S. Bureau of Labor Statistics (BLS) Application Programming Interface (API). The BLS API provides public access to economic data from all BLS programs including employment, unemployment, and labor market statistics.</p>
</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">bea.R</a> <br>
<i>Bureau of Economic Analysis API Access for R</i> <br>
<strong>GitHub Repository:</strong> <a href="https://github.com/ahmedelfatmaoui/bea.R" target="_blank">ahmedelfatmaoui/bea.R</a> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The bea.R package provides programmatic access to U.S. Bureau of Economic Analysis data through their API. This package enables researchers to easily retrieve and analyze national and regional economic statistics including GDP, national accounts, and comprehensive economic indicators.</p>
</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">urbnmapr</a> <br>
<i>State and County Maps with Alaska and Hawaii</i> <br>
<strong>GitHub Repository:</strong> <a href="https://github.com/ahmedelfatmaoui/urbnmapr" target="_blank">ahmedelfatmaoui/urbnmapr</a> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The urbnmapr package provides state and county maps for the United States with Alaska and Hawaii repositioned for better visualization. This package makes it easy to create appealing and informative choropleth maps with pre-formatted spatial data optimized for data visualization.</p>
</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">education-data-package-r</a> <br>
<i>Urban Institute Education Data Portal API for R</i> <br>
<strong>GitHub Repository:</strong> <a href="https://github.com/ahmedelfatmaoui/education-data-package-r" target="_blank">ahmedelfatmaoui/education-data-package-r</a> <br>

<button class="accordion">Package Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>The education-data-package-r provides R users with access to the Urban Institute's Education Data Portal API, containing comprehensive U.S. education datasets. Essential for education researchers, policy analysts, and anyone studying trends in American education systems.</p>
</div>

<div class="section-heading">Educational Resources and References</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">Causal Inference: The Mixtape</a> <br>
<i>Scott Cunningham's comprehensive guide to causal inference methods</i> <br>
<strong>Online Version:</strong> <a href="https://mixtape.scunning.com/" target="_blank">mixtape.scunning.com</a> <br>

<button class="accordion">Resource Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>A comprehensive online textbook covering causal inference methods for social scientists. Includes practical applications using both R, Python and Stata, covering topics like regression discontinuity, instrumental variables, difference-in-differences, and synthetic controls. Essential reading for applied economists working with observational data.</p>
</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">An Introduction to Statistical Learning</a> <br>
<i>Statistical learning methods with applications in R and Python</i> <br>
<strong>Online Version:</strong> <a href="https://www.statlearning.com/" target="_blank">statlearning.com</a> <br>

<button class="accordion">Resource Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>A foundational text for statistical learning and machine learning methods, available in both R and Python versions. Covers regression, classification, resampling methods, tree-based methods, and more. Particularly useful for economists interested in modern data science techniques and predictive modeling.</p>
</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">Python Data Science Handbook</a> <br>
<i>Essential tools for working with data in Python</i> <br>
<strong>Online Version:</strong> <a href="https://jakevdp.github.io/PythonDataScienceHandbook/" target="_blank">jakevdp.github.io/PythonDataScienceHandbook</a> <br>

<button class="accordion">Resource Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>A comprehensive guide to Python's data science ecosystem, covering NumPy, Pandas, Matplotlib, and Scikit-Learn. Excellent resource for economists looking to expand their computational toolkit beyond R, with practical examples and applications relevant to economic data analysis.</p>
</div>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">Posit Cheatsheets</a> <br>
<i>Quick reference guides for R packages and data science tools</i> <br>
<strong>Website:</strong> <a href="https://rstudio.github.io/cheatsheets/" target="_blank">rstudio.github.io/cheatsheets</a> <br>

<button class="accordion">Resource Description</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>A collection of concise reference sheets for popular R packages including ggplot2, dplyr, tidyr, and many others. Invaluable for quick syntax lookup and discovering new functions. Available in multiple languages and regularly updated to reflect the latest package versions.</p>
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

<!-- Default Statcounter code for my personal web
https://ahmedelfatmaoui.github.io/ -->
<script type="text/javascript">
var sc_project=13158462; 
var sc_invisible=1; 
var sc_security="62bc3333"; 
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js"
async></script>
<noscript><div class="statcounter"><a title="Web Analytics
Made Easy - Statcounter" href="https://statcounter.com/"
target="_blank"><img class="statcounter"
src="https://c.statcounter.com/13158462/0/62bc3333/1/"
alt="Web Analytics Made Easy - Statcounter"
referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>
<!-- End of Statcounter Code -->