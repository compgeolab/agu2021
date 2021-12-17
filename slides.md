<!--
This file defines the contents of each slide.
The reveal.js configuration can be found in index.html
-->

<!-- .slide: class="slide-title" data-background-image="assets/background.svg" data-background-size="contain" data-background-color="#000000" -->

<!-- Place the content at the bottom of the slide -->
<div class="r-stretch">
</div>

<!-- Main title page -->
<div class="lefted">

<h1 id="talk-title">
Open Science in Action: Earth
</h1>

<p id="talk-authors">
<strong>Leonardo Uieda</strong>
and
Santiago Soler
</p>

<!-- Place location and date side-by-side with affiliation logos -->
<div class="container talk-info">
<div class="col-large">

AGU 2021
<span style="margin: 0 20px">•</span>
17 December 2021

<!-- Permission to reuse and CC-BY license logo -->
<p><a href="https://creativecommons.org/licenses/by/4.0/">
<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by" style="margin: 0 10px 0 2px"></i>
CC-BY 4.0 License
</a></p>

<i class="fa fa-camera" style="margin: 0 10px 0 0"></i>
Feel free to screenshot/share/reuse/remix this presentation

</div>
<div class="col-small">

<!-- Add logos here. Need these wrappers to align them to the bottom right -->
<div class="talk-logos-container">
<div class="talk-logos">
    <img src="assets/compgeolab-banner-light.svg">
    <br>
    <img src="assets/university-of-liverpool-white.png">
    <img src="assets/conicet.png">
    <img src="assets/universidad-nacional-de-san-juan.png">
</div>
</div>

</div>
</div>

</div>

---

<!-- .slide: data-background-image="assets/gravity-disturbance.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="centered">
<div>

<img src="assets/compgeolab-banner-light.svg" style="width: 40%; margin-bottom: 6rem;">

<p style="margin-bottom: 6rem;">
We solve <b>inverse problems</b> in Geophysics
<br>
and build <b>open-source software</b>
</p>

<p style="margin-bottom: 6rem;">
Moderate compute and data
</p>

<div class="huge">

[compgeolab.org](https://www.compgeolab.org)

</div>

</div>
</div>

---

<!-- .slide: class="slide-transition" data-background-color="#0d6efd" -->

<div class="centered">
<div>

# Our approach to open science

</div>
</div>

---

<div class="centered">
<div>

Build as much as possible into open-source **from the start**

<div class="container" style="margin: 10rem 0;">
<div class="col">
<img src="assets/fatiando-banner-small-light.svg">
</div>
<div class="col">
<img src="assets/gmt-logo.png">
</div>
<div class="col">
<img src="assets/scipy-stack.svg">
</div>
</div>

<div class="fragment">

**New methods won't be used without an implementation**\*

<div class="tiny">

\* Doesn't even have to be a good one

</div>
</div>

</div>
</div>

---

<!-- .slide: data-background-image="assets/eql-gb-repo.jpg" data-background-size="contain" data-background-color="#000000" -->

<div class="centered">
<div class="quote">

**Paper == GitHub repo**
<br>
Code + Data + Figures + Text
<br>
Private at first, public on submission, archived on acceptance

</div>
</div>

---

<div class="centered">
<div>

# Tech

<div class="huge">

**Code:** Python, Jupyter, conda

**Writing:** LaTeX, Jupyter

**Review and automation:** make, GitHub, CI

</div>

</div>
</div>

---

<!-- .slide: data-background-image="assets/notebook-review.jpg" data-background-size="contain" data-background-color="#000000" -->

<div class="centered">
<div class="quote">

**Could be better:**
<br>
Notebook review on GitHub 😔
<br>
Notebooks + Make
<br>
Barrier to entry

</div>
</div>

---

# Earth Science toolkit landscape

<div class="container">
<div class="col">

* Matlab
* Fortran/C++ on HPC
* Python on laptop (Jupyter)
* Python on the cloud (Pangeo)

</div>
<div class="col">

* Bash (csh 🧙) scripts
* Google Earth Engine
* Commercial GUIs (ArcGIS, Petrel)
* OSS GUIs (QGIS, OpendTect)

</div>
</div>

---

<div class="centered">
<div class="huge">

A lot of effort to replace existing stack

<p class="fragment">
Interoperability between new and established tools
</p>

<p class="fragment">
Education of scientists on new ways of working
</p>

<p class="fragment">
Trend towards Python + GitHub + Jupyter
</p>

<p class="fragment">
Code + OSS ➡️  Openness + Reproducibility ❤️
</p>

</div>
</div>

---

<!-- .slide: data-background-image="assets/background-contact.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="centered huge">
<div>

Find out more:

[www.compgeolab.org](https://www.compgeolab.org)

</div>
</div>

---

<!-- .slide: class="slide-license" -->

<div class="centered">
<div>

<p class="license-icons">
<i class="fab fa-github"></i>
</p>

Source code for this presentation:
<br>
[github.com/compgeolab/agu2021](https://github.com/compgeolab/agu2021)

<p class="license-icons" style="margin-top: 5rem;">
<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
</p>

Unless otherwise noted,
the contents of this presentation are
licensed under the
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)

</div>
</div>
