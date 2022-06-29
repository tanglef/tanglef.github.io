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

None yet

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