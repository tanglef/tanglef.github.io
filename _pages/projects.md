---
title: "Projects"
layout: splash
permalink: /projects/
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
intro:
  - excerpt: "These are some of the projects that I made. Some were mandatory for my courses, others just for fun or in my curious mood."


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
    excerpt: "Due to `shinyapps.io` time and memory limitations per-months, the app might not be always available."
    url: "https://github.com/tanglef/proba_shiny_app"
    btn_label: "Find Out More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

## Radio-surgery: bachelor degree final project
 Bachelor degree project with Clémence Roumier and Caroline Tresse on the **skeletonization** of a shape and how to **cover the most** of it with predefined-sizes rays. Methods based on *Mathématiques et technologie* by Yvan Saint-Aubin and Christiane Rousseau (Springer 2009).

{% include feature_row id="surgery" %}

## Rshiny app for interactive probabilities
 R-Shiny app to **visualize probability distributions**, make some **probability computations** easily and **interactive** disctionnary for a general bachelor-level theorems and definitions in probabilities and statistics. This was mainly to discover bymyself the interactivity with the *R* programming and make it useful.
[Give it a try!](https://tanguylefort.shinyapps.io/probas/){: .btn}

{% include feature_row id="shiny_app" type="left" %}

