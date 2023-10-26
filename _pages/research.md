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
September 2023: <i>Peerannot: classification for crowdsourced image datasets with Python</i>
by  <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>, <a href="http://www-sop.inria.fr/members/Alexis.Joly/wiki/pmwiki.php"> A. Joly </a> and <a href="http://josephsalmon.eu/">J. Salmon </a> </summary>
<b> Abstract: </b>
Crowdsourcing is a quick and easy way to collect labels for large datasets, involving many workers. However, workers often disagree with each other. Sources of error can arise from the workers’ skills, but also from the intrinsic difficulty of the task. We present peerannot: a Python library for managing and learning from crowdsourced labels for classification. Our library allows users to aggregate labels from common noise models or train a deep learning-based classifier directly from crowdsourced labels. In addition, we provide an identification module to easily explore the task difficulty of datasets and worker capabilities. </details>
Under Review \[[Preprint](https://tanglef.github.io/computo_2023/)\] \[[peerannot library doc](https://peerannot.github.io/)\] \[[peerannot github](https://github.com/peerannot/peerannot)\]

- <details><summary>
October 2022: <i>Identify ambiguous tasks combining crowdsourced labels by weighting Areas Under the Margin</i>
by  <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>, <a href="http://www-sop.inria.fr/members/Alexis.Joly/wiki/pmwiki.php"> A. Joly </a> and <a href="http://josephsalmon.eu/">J. Salmon </a> </summary>
<b> Abstract: </b>
     In supervised learning - for instance in image classification - modern massive datasets are commonly labeled by a crowd of workers. The obtained labels in this crowdsourcing setting are then aggregated for training. The aggregation step generally leverages a per-worker trust score. Yet, such worker-centric approaches discard each task's ambiguity. Some intrinsically ambiguous tasks might even fool expert workers, which could eventually be harmful to the learning step. In a standard supervised learning setting - with one label per task - the Area Under the Margin (AUM) is tailored to identify mislabeled data. We adapt the AUM to identify ambiguous tasks in crowdsourced learning scenarios, introducing the Weighted AUM (WAUM). The WAUM is an average of AUMs weighted by task-dependent scores. We show that the WAUM can help discard ambiguous tasks from the training set, leading to better generalization or calibration performance. We report improvements over existing strategies for learning a crowd, both for simulated settings and for the CIFAR-10H, LabelMe and Music crowdsourced datasets. </details>
\[[ArXiv](https://arxiv.org/abs/2209.15380)\]\[[slides]({{ site.url }}/_data/communication/beamer_mlmtp_waum.pdf)\]


<ul>
<div style="border: 1px solid #ccc; padding: 10px; margin: 10px; display: inline-block;">
<li><details>
<summary>
  <img src="{{ site.url }}/_data/images/logo_benchopt.png" alt="Benchopt logo" style="max-width: 100px; height: auto;">
June 2022: <i>Benchopt: Reproducible, efficient and collaborative optimization benchmarks</i>
by <a href="https://tommoral.github.io/about.html">T. Moreau </a>,  <a href="https://mathurinm.github.io/">M. Massias </a>, <a href="http://alexandre.gramfort.net/">A. Gramfort </a>, <a href="https://pierreablin.com/">P. Ablin </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>,  <a href="https://twitter.com/el_pa_b">P.-A. Bannier </a>,  <a href="https://deepai.org/profile/mathieu-dagreou"> M. Dagréou </a>, <a href="https://tomdlt.github.io/#about_me">T. Dupré la Tour</a>, <a href="https://gdurif.perso.math.cnrs.fr/">G. Durif </a>, <a href="https://cassiofragadantas.github.io/">C. F. Dantas </a>, <a href="https://klopfe.github.io/">Q. Klopfenstein </a>, <a href="https://larssonjohan.com/">J. Larsson </a>, E. Lai, <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj60YnA0Nz4AhVG0RoKHeXaDxoQFnoECAsQAQ&url=https%3A%2F%2Ffr.linkedin.com%2Fin%2Fbenoit-malezieux-203283148&usg=AOvVaw38uDhnW-gQfAo8_Xfi3fm1">B. Malézieux </a>, <a href="https://t.co/Z0XdSWDuBp">B. Moufad </a>, <a href="https://tbng.github.io/">T. B. Nguyen </a>, <a href="https://twitter.com/rakotal1">A. Rakotomamonjy </a>, <a href="https://zaccharieramzi.fr/">Z. Ramzi </a>, <a href="http://josephsalmon.eu/">J. Salmon </a> and <a href="http://samuelvaiter.com/"> S. Vaiter </a></summary>
<b> Abstract: </b>
Numerical validation is at the core of machine learning research as it allows to assess the actual impact of new methods, and to confirm the agreement between theory and practice. Yet, the rapid development of the field poses several challenges: researchers are confronted with a profusion of methods to compare, limited transparency and consensus on best practices, as well as tedious re-implementation work. As a result, validation is often very partial, which can lead to wrong conclusions that slow down the progress of research. We propose Benchopt, a collaborative framework to automate, reproduce and publish optimization benchmarks in machine learning across programming languages and hardware architectures. Benchopt simplifies benchmarking for the community by providing an off-the-shelf tool for running, sharing and extending experiments. To demonstrate its broad usability, we showcase benchmarks on three standard learning tasks: l2-regularized logistic regression, Lasso, and ResNet18 training for image classification.These benchmarks highlight key practical findings that give a more nuanced view of the state-of-the-art fort hese problems, showing that for practical evaluation, the devil is in the details. We hope that Benchopt will foster collaborative work in the community hence improving the reproducibility of research findings. </details></li>
</div>
</ul>
\[[ArXiv](https://arxiv.org/pdf/2206.13424.pdf)\] \[[BibTeX](https://scholar.google.com/scholar_lookup?arxiv_id=2206.13424)\]\[[Benchopt](https://benchopt.github.io/)\]

# Talks

- <details><summary>
October 2023: <i> ChatGPT & co, Mythes and Reality. Everything you wanted to ask about Deep Learning but did not dare to</i> Séminaire culture générale, with Francois David Collin IMAG</summary> <b> Abstract: </b>
Many of us have seen the strong impact of so-called Deep Learning technologies for some time now.
This is particularly true of their "generative" side, with Large Language Models (LLMs) such as ChatGPT, GPT-4, etc., whose use has become widespread in higher education, inviting teaching staff to question these tools, from their creation to their use.
Here, we offer an overview of Deep Learning, taking a look at what data-driven learning is, and introducing the flagship of these new technologies: LLMs, their development and uses. </details>
\[[slides](https://francoisdavid.collin.pages.math.cnrs.fr/chatgpt-imag-talk/#/title-slide)\]\[[code](https://plmlab.math.cnrs.fr/francoisdavid.collin/chatgpt-imag-talk)\]

- <details><summary>
September 2023: <i>Data collection from a crowd: where is the noise coming from? </i>PhD students seminar, IMAG, Univ. Montpellier.</summary> <b> Abstract: </b>
Citizen science can increase public engagement, improve our knowledge and help models perform better. Keeping humans in the loop is a way to obtain more data, faster, at a lesser cost than if we asked experts all the time. However, citizen science often comes with an issue: we collect noisy data from a crowd of workers. For example, in image classification, what can we do when workers disagree on the label of a given image? If there is no consensus, who is at fault? Is the mistake coming from the workers’ abilities or is the image simply not clear enough to be labeled? In this talk, we present different ways to learn from crowdsourced data. In particular, we look back to how datasets were created and how label ambiguities can naturally happen along the way. </details>
\[[slides]({{ site.url }}/_data/communication/beamer_semdoc_2023.pdf)\]\[[peerannot library doc](https://peerannot.github.io/)\] \[[peerannot github](https://github.com/peerannot/peerannot)\]

- February 2023: [*ML-MTP*](https://groupes.renater.fr/wiki/ml-mtp/index) *Learning from crowds: going beyond aggregation schemes* Univ. Montpellier IMAG \[[slides](https://groupes.renater.fr/wiki/ml-mtp/_media/wiki/beamer.pdf)\]

- October 2022: [*ML-MTP*](https://groupes.renater.fr/wiki/ml-mtp/index) *Improve learning combining crowdsourced labels by weighting Areas Under the Margin* Univ. Montpellier IMAG \[[slides]({{ site.url }}/_data/communication/beamer_mlmtp_waum.pdf)\]

- July 2022: [*GDR MaDICS*](https://www.madics.fr/event/symposium-madics-4/) "Gongshow" and poster session at Quatrième édition du Symposium MaDICS - Univ. Lyon

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

- April 2022: [*Statlearn*](https://www.sfds.asso.fr/fr/group/activites_et_parrainages/activites_de_la_sfds/569-statlearn/) *Springschool* workshop on upcoming trends in statistical learning, poster session - Cargèse Corsica

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