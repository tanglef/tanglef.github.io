---
title: "Research"
permalink: /research/
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
intro:
  - excerpt: "Scientific communication: including talks, (pre)-publications, code and slides when available. *In fine* the serious page."

classes: wide
---

{% include feature_row id="intro" type="center" %}

# Publications

- <details><summary>
June 2022: <i>Benchopt: Reproducible, efficient and collaborative optimization benchmarks</i>
by [T. Moreau](https://tommoral.github.io/about.html) and [M. Massias](https://mathurinm.github.io/) and [A. Gramfort](http://alexandre.gramfort.net/) and [P. Ablin](https://pierreablin.com/) and [B. Charlier](https://imag.umontpellier.fr/~charlier/index.php?page=index) and [P.-A. Bannier](https://twitter.com/el_pa_b) and [M. Dagréou](https://deepai.org/profile/mathieu-dagreou) and [T. Dupré la Tour](https://tomdlt.github.io/#about_me) and [G. Durif](https://gdurif.perso.math.cnrs.fr/) and [C. F. Dantas](https://cassiofragadantas.github.io/) and [Q. Klopfenstein](https://klopfe.github.io/) and [J. Larsson](https://larssonjohan.com/) and E. Lai and [T. Lefort](https://tanglef.github.io/) and [B. Malézieux](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj60YnA0Nz4AhVG0RoKHeXaDxoQFnoECAsQAQ&url=https%3A%2F%2Ffr.linkedin.com%2Fin%2Fbenoit-malezieux-203283148&usg=AOvVaw38uDhnW-gQfAo8_Xfi3fm1) and [B. Moufad](https://t.co/Z0XdSWDuBp) and [T. B. Nguyen](https://tbng.github.io/) and [A. Rakotomamonjy](https://twitter.com/rakotal1) and [Z. Ramzi](https://zaccharieramzi.fr/) and [J. Salmon](http://josephsalmon.eu/) and [S. Vaiter](http://samuelvaiter.com/)</summary>
<b> Abstract: </b>
Numerical validation is at the core of machine learning research as it allows to assess the actual impactof new methods, and to confirm the agreement between theory and practice. Yet, the rapid developmentof the field poses several challenges: researchers are confronted with a profusion of methods to compare,limited transparency and consensus on best practices, as well as tedious re-implementation work. Asa result, validation is often very partial, which can lead to wrong conclusions that slow down theprogress of research. We proposeBenchopt, a collaborative framework to automate, reproduce and publishoptimization benchmarks in machine learning across programming languages and hardware architectures.Benchoptsimplifies benchmarking for the community by providing an off-the-shelf tool for running, sharingand extending experiments. To demonstrate its broad usability, we showcase benchmarks on three standardlearning tasks:`2-regularized logistic regression, Lasso, and ResNet18 training for image classification.These benchmarks highlight key practical findings that give a more nuanced view of the state-of-the-art forthese problems, showing that for practical evaluation, the devil is in the details. We hope thatBenchoptwill foster collaborative work in the community hence improving the reproducibility of research findings. </details>
\[[ArXiv](https://arxiv.org/pdf/2206.13424.pdf)\] \[[BibTeX](https://scholar.googleusercontent.com/scholar.bib?q=info:kvK8-VeiojAJ:scholar.google.com/&output=citation&scisdr=CgXQPsd5EJySkFGE0ww:AAGBfm0AAAAAYsGCywym0wydv8Rtk4shOCWMWyNcCnOp&scisig=AAGBfm0AAAAAYsGCy3xYRatDfssfEZR1EHo8b_yIDwcq&scisf=4&ct=citation&cd=-1&hl=fr)\]\[[Benchopt](https://benchopt.github.io/)\]

# Talks

- <details><summary>
June 2022: <i>Crowdsourcing label noise simulation on image classification tasks </i> at Journées des Statistiques de France (JDS) 2022 Univ. Lyon.</summary> <b> Abstract: </b>
It is common to collect labelled datasets using crowdsourcing.
Yet, labels quality depends deeply on the task difficulty and on the workers abilities.
With such datasets, the lack of ground truth makes it hard to assess the quality of annotations.
There are few open-access crowdsourced datasets, and even fewer that provide both heterogeneous tasks in difficulty and all workers answers before the aggregation.
We propose a new crowdsourcing simulation framework with quality control.
This allows us to evaluate different empirical learning strategies empirically from the obtained labels.
Our goal is to separate different sources of noise:
workers that do not provide any information on the true label against poorly performing workers, useful on easy tasks.</details>
\[[slides]({{ site.url }}/_data/communication/beamer_jds_tlefort.pdf)\]

- June 2022: <i>Workshop: How to create a professional and personal website easily </i> at SemDoc (PhD seminar) - Univ. Montpellier IMAG

- <details><summary>
November 29 2021: <i>High dimensional optimization for penalized linear models with interactions using graphics card computational power</i>, at Probability and statistics (EPS) team seminar - Univ. Montpellier IMAG (content from my master's thesis internship)</summary> <b>Abstract:</b>
Linear models are used in statistics for their simplicity and the interpretability of the results.
On genomics datasets, large dimensions need robust methods that induce sparsity to select interpretable active features for biologists. In addition to the main features, we also capture the effects of the interactions, which increase the dimension of the problem and the multicolinearity.
To counteract these issues, we use the Elastic-Net on the augmented problem. Coordinate Descent is mostly used nowadays for that, but there are other methods available.
We exploit the structure of our problem with first order interactions to use parallelized proximal gradient descent algorithms.
Those are known to be more computationally demanding in order of magnitude, but parallelizing on a graphics card let us be as fast or faster in some situations.</details>
\[[slides]({{ site.url }}/_data/communication/internship_beamer.pdf)\]
\[[code](https://github.com/tanglef/interactionsmodel)\]

- October 28 2021: *Introduction to neural network* with [Joseph Salmon](http://josephsalmon.eu/), at ML-MTP seminar - Univ. Montpellier IMAG. (session 0 for reading group on *Deep Learning: a statistical viewpoint*)<br>
\[[slides]({{ site.url }}/_data/communication/tuto_deep.pdf)\] \[[code]({{ site.url }}/_data/communication/code_tuto_deep.zip)\]

- April 29 2021: Paper club *Ridge Regularization: an Essential Concept in Data Science by Trevor Hastie* with [Florent Bascou](https://bascouflorent.github.io/), at ML-MTP seminar - Univ. Montpellier IMAG <br>
 \[[paper](https://arxiv.org/pdf/2006.00371.pdf)\] \[[slides]({{ site.url }}/_data/communication/ridge_ml_mtp.pdf)\]