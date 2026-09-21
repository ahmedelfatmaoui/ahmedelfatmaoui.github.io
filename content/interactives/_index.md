---
title: ""
description: "Interactive economics exercises with guided questions, dynamic graphs, and immediate feedback."
---

<style>
.section-heading {
font-size: 120%;
font-weight: bold;
color: #333;
margin-top: 20px;
margin-bottom: 15px;
border-bottom: 2px solid #1976d2;
padding-bottom: 5px;
}

.page-intro {
margin: 0 0 24px;
color: #555;
}

.interactive-item {
margin-bottom: 24px;
}

.interactive-title {
font-size: 100%;
font-weight: bold;
}

button.accordion {
display: block;
font: 14px/1.5 Lato, "Helvetica Neue", Helvetica, Arial, sans-serif;
cursor: pointer;
padding: 0;
border: none;
text-align: left;
outline: none;
font-size: 100%;
transition: 0.3s;
background-color: #f8f8f8;
}

button.accordion.active,
button.accordion:hover {
background-color: #f8f8f8;
}

button.accordion:after {
content: " [+] ";
font-size: 90%;
color: #777;
float: left;
margin-left: 1px;
}

button.accordion.active:after {
content: " [\2212] ";
}

div.panel {
padding: 10px;
margin-top: 5px;
display: none;
background-color: #f1f1f1;
color: #666;
font-size: 100%;
}

div.panel.show {
display: block;
}

div.panel p {
margin: 0;
}
</style>

<div class="section-heading">Interactives</div>

<p class="page-intro">Explore economic concepts through guided scenarios, dynamic graphs, and immediate feedback.</p>

<div class="interactive-item">
<a class="interactive-title" href="/externalities_practice.html" target="_blank" rel="noopener noreferrer">Externalities Practice</a><br>
<i>Positive and negative production and consumption externalities</i><br>
<strong>Launch:</strong> <a href="/externalities_practice.html" target="_blank" rel="noopener noreferrer">Open Externalities Practice</a>
<button class="accordion">Description</button>
<div class="panel">
<p>Work through a random set of externality scenarios one step at a time. Identify who creates the spillover, whether it helps or harms third parties, how the social curve differs from the private curve, whether the market produces too much or too little, and which policy moves the market toward the social optimum.</p>
</div>
</div>

<div class="interactive-item">
<a class="interactive-title" href="/demand_curve_practice.html" target="_blank" rel="noopener noreferrer">Deriving the Demand Curve: Practice</a><br>
<i>Consumer choice, budget lines, indifference curves, and demand</i><br>
<strong>Launch:</strong> <a href="/demand_curve_practice.html" target="_blank" rel="noopener noreferrer">Open Demand Curve Practice</a>
<button class="accordion">Description</button>
<div class="panel">
<p>Work through three random consumer scenarios to derive a demand curve from utility-maximizing choices. The exercise uses interactive graphs and guided questions to connect changes in a good's price with budget lines, optimal bundles, and movements along the demand curve.</p>
</div>
</div>

<div class="interactive-item">
<a class="interactive-title" href="/grossman-ppf.html" target="_blank" rel="noopener noreferrer">Why the Health–Bread Frontier Bends Backward</a><br>
<i>The production possibilities frontier for health and home goods in the Grossman model</i><br>
<strong>Launch:</strong> <a href="/grossman-ppf.html" target="_blank" rel="noopener noreferrer">Open Grossman PPF Interactive</a>
<button class="accordion">Description</button>
<div class="panel">
<p>Explore how allocating time among health production, sickness, and home-good production creates a backward-bending frontier. Move along the frontier, examine key points, connect preferences to choices, check your understanding, and see how education or medical efficiency shifts the entire curve.</p>
</div>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
    acc[i].onclick = function() {
        this.classList.toggle("active");
        this.nextElementSibling.classList.toggle("show");
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
