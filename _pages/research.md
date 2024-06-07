---
title: "Research"
permalink: /research/
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
intro:
  - excerpt: "Scientific communication: including talks, (pre)-publications, code and slides when available. *In fine* the serious page."
toc: true
toc_sticky: true
toc_label: "Contents"
toc_icon: "swatchbook"
classes: wide
---

{% include feature_row id="intro" type="center" %}

# Publications

## Journals

- <details><summary>
2024 <i>
Cooperative learning of Pl@ntNet's Artificial Intelligence algorithm: how does it work and how can we improve it?
</i>
by <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://x.com/antoineaffouard"> A. Affouard </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>, <a href="https://inria.hal.science/search/index/?qa%5Bauth_t%5D%5B%5D=Jean-Christophe%2BLombardo&sort=producedDate_tdate+desc"> J-C. Lombardo </a>, M. Chouet, <a href="https://scholar.google.fr/citations?user=zBZYEzAAAAAJ&hl=fr"> H. Goëau </a>,  <a href="http://josephsalmon.eu/">J. Salmon </a>, <a href="https://agents.cirad.fr/Pierre+BONNET"> P. Bonnet </a> and <a href="http://www-sop.inria.fr/members/Alexis.Joly/wiki/pmwiki.php"> A. Joly </a> (under review in Methods in Ecology and Evolution) </summary>
<b> Abstract: </b>
   Deep learning models for plant species identification rely on large annotated datasets. The PlantNet system enables global data collection by allowing users to upload and annotate plant observations, leading to noisy labels due to diverse user skills. Achieving consensus is crucial for training, but the vast scale of collected data makes traditional label aggregation strategies challenging. Existing methods either retain all observations, resulting in noisy training data or selectively keep those with sufficient votes, discarding valuable information. Additionally, as many species are rarely observed, user expertise can not be evaluated as an inter-user agreement: otherwise, botanical experts would have a lower weight in the AI training step than the average user. Our proposed label aggregation strategy aims to cooperatively train plant identification AI models. This strategy estimates user expertise as a trust score per user based on their ability to identify plant species from crowdsourced data. The trust score is recursively estimated from correctly identified species given the current estimated labels. This interpretable score exploits botanical experts' knowledge and the heterogeneity of users. Subsequently, our strategy removes unreliable observations but retains those with limited trusted annotations, unlike other approaches. We evaluate PlantNet's strategy on a released large subset of the PlantNet database focused on European flora, comprising over 6M observations and 800K users. We demonstrate that estimating users' skills based on the diversity of their expertise enhances labeling performance. Our findings emphasize the synergy of human annotation and data filtering in improving AI performance for a refined dataset. We explore incorporating AI-based votes alongside human input. This can further enhance human-AI interactions to detect unreliable observations.  </details>
\[[ArXiv](https://arxiv.org/abs/2406.03356)\]



<ul>
<li><details>
<summary>
  <img src="{{ site.url }}/_data/images/pipeline_peerannot.png" style="max-width: 100px; height: auto; float: left; margin-right: 5px;">
2024 <i>Peerannot: classification for crowdsourced image datasets with Python</i>
by  <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>, <a href="http://www-sop.inria.fr/members/Alexis.Joly/wiki/pmwiki.php"> A. Joly </a> and <a href="http://josephsalmon.eu/">J. Salmon </a> in Computo </summary>
<b> Abstract: </b>
Crowdsourcing is a quick and easy way to collect labels for large datasets, involving many workers. However, workers often disagree with each other. Sources of error can arise from the workers’ skills, but also from the intrinsic difficulty of the task. We present peerannot: a Python library for managing and learning from crowdsourced labels for classification. Our library allows users to aggregate labels from common noise models or train a deep learning-based classifier directly from crowdsourced labels. In addition, we provide an identification module to easily explore the task difficulty of datasets and worker capabilities. </details>
</li>
<p>
  [<a href="https://computo.sfds.asso.fr/published-202402-lefort-peerannot/">Paper</a>]
  [<a href="https://peerannot.github.io/">peerannot library doc</a>]
  [<a href="https://github.com/peerannot/peerannot">peerannot github</a>]
</p>
</ul>

- <details><summary>
2024 <i>Identify ambiguous tasks combining crowdsourced labels by weighting Areas Under the Margin</i>
by <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>, <a href="http://www-sop.inria.fr/members/Alexis.Joly/wiki/pmwiki.php"> A. Joly </a> and <a href="http://josephsalmon.eu/">J. Salmon </a> in TMLR </summary>
<b> Abstract: </b>
     In supervised learning - for instance in image classification - modern massive datasets are commonly labeled by a crowd of workers. The obtained labels in this crowdsourcing setting are then aggregated for training. The aggregation step generally leverages a per-worker trust score. Yet, such worker-centric approaches discard each task's ambiguity. Some intrinsically ambiguous tasks might even fool expert workers, which could eventually be harmful to the learning step. In a standard supervised learning setting - with one label per task - the Area Under the Margin (AUM) is tailored to identify mislabeled data. We adapt the AUM to identify ambiguous tasks in crowdsourced learning scenarios, introducing the Weighted AUM (WAUM). The WAUM is an average of AUMs weighted by task-dependent scores. We show that the WAUM can help discard ambiguous tasks from the training set, leading to better generalization or calibration performance. We report improvements over existing strategies for learning a crowd, both for simulated settings and for the CIFAR-10H, LabelMe and Music crowdsourced datasets. </details>
\[[ArXiv](https://arxiv.org/abs/2209.15380)\]\[[slides]({{ site.url }}/_data/communication/beamer_mlmtp_waum.pdf)\] \[[Openreview](https://openreview.net/forum?id=raD846nj2q&noteId=OKobldgiNW)\]


## In Proceedings of Conferences

### International Conferences

<ul>
<li><details>
<summary>
  <img src="{{ site.url }}/_data/images/logo_benchopt.png" alt="Benchopt logo" style="max-width: 100px; height: auto; float: left; margin-right: 5px;">
June 2022: <i>Benchopt: Reproducible, efficient and collaborative optimization benchmarks</i>, NeurIPS 2022 by <a href="https://tommoral.github.io/about.html">T. Moreau </a>,  <a href="https://mathurinm.github.io/">M. Massias </a>, <a href="http://alexandre.gramfort.net/">A. Gramfort </a>, <a href="https://pierreablin.com/">P. Ablin </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>,  <a href="https://twitter.com/el_pa_b">P.-A. Bannier </a>,  <a href="https://deepai.org/profile/mathieu-dagreou"> M. Dagréou </a>, <a href="https://tomdlt.github.io/#about_me">T. Dupré la Tour</a>, <a href="https://gdurif.perso.math.cnrs.fr/">G. Durif </a>, <a href="https://cassiofragadantas.github.io/">C. F. Dantas </a>, <a href="https://klopfe.github.io/">Q. Klopfenstein </a>, <a href="https://larssonjohan.com/">J. Larsson </a>, E. Lai, <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj60YnA0Nz4AhVG0RoKHeXaDxoQFnoECAsQAQ&url=https%3A%2F%2Ffr.linkedin.com%2Fin%2Fbenoit-malezieux-203283148&usg=AOvVaw38uDhnW-gQfAo8_Xfi3fm1">B. Malézieux </a>, <a href="https://t.co/Z0XdSWDuBp">B. Moufad </a>, <a href="https://tbng.github.io/">T. B. Nguyen </a>, <a href="https://twitter.com/rakotal1">A. Rakotomamonjy </a>, <a href="https://zaccharieramzi.fr/">Z. Ramzi </a>, <a href="http://josephsalmon.eu/">J. Salmon </a> and <a href="http://samuelvaiter.com/"> S. Vaiter </a></summary>
<b> Abstract: </b>
Numerical validation is at the core of machine learning research as it allows to assess the actual impact of new methods, and to confirm the agreement between theory and practice. Yet, the rapid development of the field poses several challenges: researchers are confronted with a profusion of methods to compare, limited transparency and consensus on best practices, as well as tedious re-implementation work. As a result, validation is often very partial, which can lead to wrong conclusions that slow down the progress of research. We propose Benchopt, a collaborative framework to automate, reproduce and publish optimization benchmarks in machine learning across programming languages and hardware architectures. Benchopt simplifies benchmarking for the community by providing an off-the-shelf tool for running, sharing and extending experiments. To demonstrate its broad usability, we showcase benchmarks on three standard learning tasks: l2-regularized logistic regression, Lasso, and ResNet18 training for image classification.These benchmarks highlight key practical findings that give a more nuanced view of the state-of-the-art fort hese problems, showing that for practical evaluation, the devil is in the details. We hope that Benchopt will foster collaborative work in the community hence improving the reproducibility of research findings. </details></li>
<p>
  [<a href="https://arxiv.org/pdf/2206.13424.pdf">ArXiv</a>]
  [<a href="https://scholar.google.com/scholar_lookup?arxiv_id=2206.13424">BibTeX</a>]
  [<a href="https://benchopt.github.io/">Benchopt</a>]
</p>
</ul>

### National Conferences

<ul>
  <li>
    <details>
      <summary>
      <img src="{{ site.url }}/_data/images/shap_cap.png" alt="shapley values for workers" style="max-width: 100px; height: auto; float: left; margin-right: 5px;">
        July 2024: <i>Weighted majority vote using Shapley values in crowdsourcing</i>, CAp 2024  by  <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>,  <a href="http://www-sop.inria.fr/members/Alexis.Joly/wiki/pmwiki.php"> A. Joly and <a href="http://josephsalmon.eu/">J. Salmon </a> </a> .
      </summary>
      <b>Abstract:</b>
      Crowdsourcing has emerged as a pivotal paradigm for harnessing collective intelligence to solve data annotation tasks. Effective label aggregation, crucial for leveraging the diverse judgments of contributors, remains a fundamental challenge in crowdsourcing systems. This paper introduces a novel label aggregation strategy based on Shapley values, a concept originating from cooperative game theory. By integrating Shapley values as worker weights into the Weighted Majority Vote label aggregation (WMV), our proposed framework aims to address the interpretability of weights assigned to workers. This aggregation reduces the complexity of probabilistic models and the difficulty of the final interpretation of the aggregation from the workers’ votes. We show improved accuracy against other WMV-based label aggregation strategies. We demonstrate the efficiency of our strategy on various real datasets to explore multiple crowdsourcing scenarios.
    </details>
    <p>
      [<a href="{{ site.url }}/_data/papers/cap24.pdf">paper</a>]
    </p>
  </li>
    <li>
    <details>
      <summary>
        May 2024: <i>peerannot: A framework for label aggregation in crowdsourced datasets</i>, JDS 2024 by  A. Dubar, <a href="https://tanglef.github.io/">T. Lefort </a> and <a href="http://josephsalmon.eu/">J. Salmon </a>.
      </summary>
      <b>Abstract:</b>
      Ce travail présente peerannot, une librairie de classification de données dont les étiquettes sont générées par production participative. Elle est écrite en Python et permet d’établir une comparaison des méthodes de classification par agŕegation avec d'utres librairies de référence.    </details>
    <p>
      [<a href="https://hal.science/hal-04562830v1">paper</a>]
    </p>
  </li>
  <li>
    <details>
      <summary>
        May 2024: <i>Cooperative learning of Pl@ntNet’s Artificial Intelligence algorithm using label aggregation</i>, JDS 2024 by  <a href="https://tanglef.github.io/">T. Lefort </a>, A. Affouard <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>, <a href="http://josephsalmon.eu/">J. Salmon </a> P. Bonnet and <a href="http://www-sop.inria.fr/members/Alexis.Joly/wiki/pmwiki.php"> A. Joly </a> .
      </summary>
      <b>Abstract:</b>
The Pl@ntNet system enables global data collection by allowing users to upload and annotate plant observations, leading to noisy labels due to diverse user skills. Achieving consensus is crucial for training, but the vast scale of collected data makes traditional label aggregation strategies challenging. Additionally, as many species are rarely observed, user expertise can not be evaluated as an inter-user agreement: otherwise, botanical experts would have a lower weight in the training step than the average user as they have fewer but precise  articipation. Our proposed label aggregation strategy aims to cooperatively train plant identification models. This strategy estimates user expertise as a trust score per worker based on their ability to identify plant species from crowdsourced data.
The trust score is recursively estimated from correctly identified species given the current estimated labels. This interpretable score exploits botanical experts’ knowledge and the heterogeneity of users. We evaluate our strategy on a large subset of the Pl@ntNet database focused on European flora, comprising over 6 000 000 observations and 800 000 users. We
demonstrate that estimating users’ skills based on the diversity of their expertise enhances labeling performance.
    </details>
    <p>
      [<a href="{{ site.url }}/_data/papers/jds24.pdf">paper</a>]
    </p>
  </li>
  <li>
    <details>
      <summary>
        July 2023: <i>Weighting areas under the margin in crowdsourced datasets</i>, JDS 2023 by  <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>, <a href="http://www-sop.inria.fr/members/Alexis.Joly/wiki/pmwiki.php"> A. Joly </a> and <a href="http://josephsalmon.eu/">J. Salmon </a>.
      </summary>
      <b>Abstract:</b>
In supervised learning — for instance in image classification — modern massive datasets are commonly labeled by a crowd of workers. Labeling errors can happen because of the workers abilities or tasks identification difficulty. Some intrinsically ambiguous tasks might fool expert workers, which could eventually be harmful to the learning step. In a standard supervised learning setting — with one label per task — the Area Under the Margin (AUM) is tailored to identify mislabeled data. We adapt the AUM to identify ambiguous tasks in crowdsourced learning scenarios, introducing the Weighted AUM (WAUM). The WAUM is an average of AUMs weighted by task-dependent scores. We show that the WAUM can help discard ambiguous tasks from the training set, leading to better generalization or calibration performance.
    </details>
    <p>
      [<a href="{{ site.url }}/_data/papers/jds23.pdf">paper</a>]
    </p>
  </li>
  <li>
    <details>
      <summary>
        <img src="{{ site.url }}/_data/images/prob_diff.png" alt="difficulty simulation" style="max-width: 100px; height: auto; float: left; margin-right: 5px;">
        June 2022: <i>Crowdsourcing label noise simulation on image classification tasks</i>, JDS 2022 by  <a href="https://tanglef.github.io/">T. Lefort </a>, <a href="https://imag.umontpellier.fr/~charlier/index.php?page=index">B. Charlier </a>, <a href="http://www-sop.inria.fr/members/Alexis.Joly/wiki/pmwiki.php"> A. Joly </a> and <a href="http://josephsalmon.eu/">J. Salmon </a>.
      </summary>
      <b>Abstract:</b>
      It is common to collect labeled datasets using crowdsourcing. Yet, label quality depends deeply on the task difficulty and on the workers' abilities. With such datasets, the lack of ground truth makes it hard to assess the quality of annotations. There are few open-access crowdsourced datasets, and even fewer that provide both heterogeneous tasks in difficulty and all workers' answers before the aggregation. We propose a new crowdsourcing simulation framework with quality control. This allows us to evaluate different empirical learning strategies empirically from the obtained labels. Our goal is to separate different sources of noise: workers that do not provide any information on the true label against poorly performing workers, useful on easy tasks.
    </details>
    <p>
      [<a href="{{ site.url }}/_data/papers/jds22.pdf">paper</a>]
    </p>
  </li>
</ul>

# Talks

- May 2024: *Cooperative data enrichment algorithms* at [Journées des Statistiques de France (JDS) 2024](https://jds2024.sciencesconf.org/resource/page/id/18) Univ. Bordeaux.
[<a href="{{ site.url }}/_data/communication/beamer_jds24.pdf">slides</a>]

<ul>
  <li>
    <details>
      <summary>
        <img src="{{ site.url }}/_data/images/Plantnet_scheme.png" alt="plantnet talk marbec" style="max-width: 100px; height: auto; float: left; margin-right: 5px;">
        March 2024 <i>Apprentissage collaboratif d'espèces de plantes et agrégation de labels dans Pl@ntNet</i> <a href="https://docs.google.com/document/d/1w7YNvQG4v7QCJj86sjO4PLqOYPOT4QTOD8Am18GgT2Q/edit#heading=h.607qmvjxwu93">IA-ECO seminar </a>, UMR MARBEC
      </summary>
      <b>Abstract:</b>
        Deep learning models for plant species identification rely on large annotated datasets. The Pl@ntNet system enables global data collection by allowing users to upload and annotate plant observations, leading to noisy labels due to diverse user skills. Achieving consensus is crucial for training, but the vast scale of collected data (number of observations, users and species) makes traditional label aggregation strategies challenging. Existing methods either retain all observations, resulting in noisy training data or selectively keep those with sufficient votes, discarding valuable information. Additionally, as many species are rarely observed, user expertise can not be evaluated as an inter-user agreement: otherwise, botanical experts would have a lower weight in the AI training step than the average user.
        Our proposed label aggregation strategy aims to cooperatively train plant identification AI models. This strategy estimates user expertise as a trust score per worker based on their ability to identify plant species from crowdsourced data. The trust score is recursively estimated from correctly identified species given the current estimated labels. This interpretable score exploits botanical experts’ knowledge and the heterogeneity of users. Subsequently, our strategy removes unreliable observations but retains those with limited trusted annotations, unlike other approaches.
        We evaluate our strategy on a large subset of the Pl@ntNet database focused on European flora, comprising over 6M observations and 800K users. This anonymized dataset of votes and observations is released [openly](https://doi.org/10.5281/zenodo.10782465). We demonstrate that estimating users’ skills based on the diversity of their expertise enhances labeling performance.
        Our findings emphasize the synergy of human annotation and data filtering in improving AI performance for a refined training dataset. We explore incorporating AI-based votes alongside human input in the label aggregation. This can further enhance human-AI interactions to detect unreliable observations (even with few votes).
    </details>
    <p>
      [<a href="{{ site.url }}/_data/communication/Cooperative_learning_of_Pl_ntNet_s_Artificial_Intelligence_algorithm.pdf">slides</a>]
    </p>
  </li>
  <li>
    <details>
      <summary>
        <img src="{{ site.url }}/_data/images/chat_gpt_talk.png" alt="ChatGPT talk" style="max-width: 100px; height: auto; float: left; margin-right: 5px;">
        October 2023: <i>ChatGPT & co, Myths and Reality. Everything you wanted to ask about Deep Learning but did not dare to</i> Séminaire culture générale, with Francois David Collin IMAG
      </summary>
      <b>Abstract:</b>
      Many of us have seen the strong impact of so-called Deep Learning technologies for some time now. This is particularly true of their "generative" side, with Large Language Models (LLMs) such as ChatGPT, GPT-4, etc., whose use has become widespread in higher education, inviting teaching staff to question these tools, from their creation to their use. Here, we offer an overview of Deep Learning, taking a look at what data-driven learning is, and introducing the flagship of these new technologies: LLMs, their development, and uses.
    </details>
    <p>
      [<a href="{{ site.url }}/_data/chatgpt_talk/public/index.html">slides</a>]
      [<a href="https://plmlab.math.cnrs.fr/francoisdavid.collin/chatgpt-imag-talk">code</a>]
    </p>
  </li>
</ul>


- <details><summary>
September 2023: <i>Data collection from a crowd: where is the noise coming from? </i>PhD students seminar, IMAG, Univ. Montpellier.</summary> <b> Abstract: </b>
Citizen science can increase public engagement, improve our knowledge and help models perform better. Keeping humans in the loop is a way to obtain more data, faster, at a lesser cost than if we asked experts all the time. However, citizen science often comes with an issue: we collect noisy data from a crowd of workers. For example, in image classification, what can we do when workers disagree on the label of a given image? If there is no consensus, who is at fault? Is the mistake coming from the workers’ abilities or is the image simply not clear enough to be labeled? In this talk, we present different ways to learn from crowdsourced data. In particular, we look back to how datasets were created and how label ambiguities can naturally happen along the way. </details>
\[[slides]({{ site.url }}/_data/communication/beamer_semdoc_2023.pdf)\]\[[peerannot library doc](https://peerannot.github.io/)\] \[[peerannot github](https://github.com/peerannot/peerannot)\]

- July 2023: *Weighting areas under the margin in crowdsourced datasets* at [Journées des Statistiques de France (JDS) 2023](https://jds2023.sciencesconf.org/resource/page/id/19) Univ. Bruxelles.


<ul>
  <li>
    <img src="{{ site.url }}/_data/images/conal.png" alt="conal" style="max-width: 100px; height: auto; float: left; margin-right: 5px;">
    February 2023: <a href="https://groupes.renater.fr/wiki/ml-mtp/index"><i>ML-MTP</i></a> <i>Learning from crowds: going beyond aggregation schemes</i> Univ. Montpellier IMAG
    <p>
      [<a href="https://groupes.renater.fr/wiki/ml-mtp/_media/wiki/beamer.pdf">slides</a>]
    </p>
  </li>
</ul>


- October 2022: [*ML-MTP*](https://groupes.renater.fr/wiki/ml-mtp/index) *Improve learning combining crowdsourced labels by weighting Areas Under the Margin* Univ. Montpellier IMAG \[[slides]({{ site.url }}/_data/communication/beamer_mlmtp_waum.pdf)\]

- July 2022: [*GDR MaDICS*](https://www.madics.fr/event/symposium-madics-4/) "Gongshow" and poster session at Quatrième édition du Symposium MaDICS - Univ. Lyon


<ul>
  <li>
    <details>
      <summary>
        <img src="{{ site.url }}/_data/images/prob_diff.png" alt="difficulty simulation" style="max-width: 100px; height: auto; float: left; margin-right: 5px;">
        June 2022: <i>Crowdsourcing label noise simulation on image classification tasks</i> at Journées des Statistiques de France (JDS) 2022 Univ. Lyon.
      </summary>
      <b>Abstract:</b>
      It is common to collect labeled datasets using crowdsourcing. Yet, label quality depends deeply on the task difficulty and on the workers' abilities. With such datasets, the lack of ground truth makes it hard to assess the quality of annotations. There are few open-access crowdsourced datasets, and even fewer that provide both heterogeneous tasks in difficulty and all workers' answers before the aggregation. We propose a new crowdsourcing simulation framework with quality control. This allows us to evaluate different empirical learning strategies empirically from the obtained labels. Our goal is to separate different sources of noise: workers that do not provide any information on the true label against poorly performing workers, useful on easy tasks.
    </details>
    <p>
      [<a href="{{ site.url }}/_data/communication/beamer_jds_tlefort.pdf">slides</a>]
    </p>
  </li>
</ul>


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


<ul>
  <li>
    <img src="{{ site.url }}/_data/images/ridge_dd.png" alt="double desent ridge" style="max-width: 100px; height: auto; float: left; margin-right: 5px;">
    April 29, 2021: Paper club <i>Ridge Regularization: an Essential Concept in Data Science by Trevor Hastie</i> with <a href="https://bascouflorent.github.io/">Florent Bascou</a> at ML-MTP seminar - Univ. Montpellier IMAG
    <p>
      [<a href="https://arxiv.org/pdf/2006.00371.pdf">paper</a>]
      [<a href="{{ site.url }}/_data/communication/ridge_ml_mtp.pdf">slides</a>]
    </p>
  </li>
</ul>
