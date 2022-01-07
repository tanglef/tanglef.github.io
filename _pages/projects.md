---
title: "Projects"
layout: splash
permalink: /projects/
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
intro:
  - excerpt: "These are some of the projects that I made. Some
  are from my PhD. Some were mandatory for my courses, others just for fun or in my curious mood."


surgery:
  - image_path: /_data/images/unicorn.png
    image_caption: "Just a random unicorn"
    alt: "Morphological skeleton of a unicorn"
    title: "Skeletonization of a shape"
    excerpt: "The first step: get the **morphological skeleton** of a shape."
    url: "https://github.com/tanglef/project_radiosurgery_l3"
    btn_label: "Find Out More"
    btn_class: "btn--primary"
  - image_path: /_data/images/rec_surgery.png
    title: "Radiosurgery on a rectangle"
    excerpt: "Try the algorithm on a simple shape first... more secure **especially if its related to surgery**."
  - image_path: /_data/images/surgery.png
    alt: "Radiosurgery method"
    title: "Radiosurgery on a tumor"
    excerpt: "We can then apply the algorithm to more complex shapes: *eg* a cerebral tumor."

shiny_app:
  - image_path: /_data/images/shiny_app.png
    alt: "main page app"
    title: "Presentation of the app"
    excerpt: "Due to `shinyapps.io` time and memory limitations per-months, the app might not be always available, hence the local run option."
    url: "https://github.com/tanglef/proba_shiny_app"
    btn_label: "Find Out More"
    btn_class: "btn--primary"

chaoseverywhere:
  - image_path: https://chaoseverywhere.readthedocs.io/en/latest/_images/3d_vision.svg
    alt: "mandelbrot_3D"
    title: "3D speed of convergence in the Mandelbrot set"
    excerpt: "Use of the `Mayavi` library to make 3D visualizations."
    url: "https://github.com/tanglef/chaoseverywhere/"
    btn_label: "Find Out More"
    btn_class: "btn--primary"
  - image_path: https://chaoseverywhere.readthedocs.io/en/latest/_static/logo1_f.svg
    alt: "logo"
    title: "Package logo"
    excerpt: "When the bifurcation diagram and the Mandelbrot set collide... That makes **Chaoseverywhere**."
  - image_path: https://chaoseverywhere.readthedocs.io/en/latest/_images/3d_transform.svg
    title: "Transformed Mandelbrot set"
    excerpt: "Let the user apply any transformation on the Mandelbrot sequence."
---

{% include feature_row id="intro" type="center" %}

## Chaoseverywhere package

 The main goal of this project was to create a **fully-documented Python package** that allows the user to visualization the link between the bifurcation diagram of the logistic map and the Mandelbrot set. Software Devlopment group project. Made with Coiffier Ophélie and Gaizi Ibrahim.

<a href="https://chaoseverywhere.readthedocs.io/en/latest/index.html" class="btn btn-primary">Click here to go see the doc</a>
(don't forget to take a look at the <a href="https://chaoseverywhere.readthedocs.io/en/latest/chaos/gallery_mayavi/gallery_mayavi.html" class="btn btn-primary">galleries</a>)!

 {% include feature_row id="chaoseverywhere" %}

## Radio-surgery: bachelor degree final project
 Bachelor degree project with Clémence Roumier and Caroline Tresse on the **skeletonization** of a shape and how to **cover the most** of it with predefined-sizes rays. Methods based on *Mathématiques et technologie* by Yvan Saint-Aubin and Christiane Rousseau (Springer 2009).

{% include feature_row id="surgery" %}

## Rshiny app for interactive probabilities
 R-Shiny app to **visualize probability distributions**, make some **probability computations** easily and **interactive** dictionnary for a general bachelor-level theorems and definitions in probabilities and statistics. This was mainly to discover by my self the interactivity with the *R* programming and make it useful.

 If you prefer to run it locally, open **RStudio** or any alternative and enter in the console the following lines. You might need to install a few packages first.

```R
# install.packages(c("shiny", "plotly", "rsconnect", "shinydashboard"))
library(shiny)
runGitHub( "proba_shiny_app", "tanglef")
```

<a href="https://tanguylefort.shinyapps.io/probas/" class="btn btn-primary">Give it a try!</a>

{% include feature_row id="shiny_app" type="left" %}