---
layout: page
permalink: /
title: Home
description: AI researcher focused on interpretable, multimodal, and aligned AI — PhD @ETH AI Center; graduted from École Polytechnique Paris and ETH Zürich.

profile:
  image: avatar.jpg
  address: >

nav: false
news: true # includes a list of news items
---

## About me

<div class="row">
  <div class="col-md-8" markdown="1">
  I recently completed my PhD as a Doctoral Fellow at the [ETH AI Center](https://ai.ethz.ch/). My work focuses on explainability for large language models, graph neural networks, and multimodal architectures, with applications in health, climate, and social systems.

  My main interests include:

  - AI explainability: model-agnostic, attribution-based XAI, semantic perturbations, mechanistic interpretability
  - Deep learning on graphs: GNN explainability, network analysis, graph theory
  - Multimodal explainability: image, text, and graph representations
  - Generative AI for molecular design and drug discovery
  - AI applications in health, climate, and social systems

  I worked within the [ETH AI Center](https://ai.ethz.ch/), supervised by Prof. Mennatallah El-Assady ([IVIA Lab](https://ivia.ethz.ch/)) and Prof. [Andreas Krause](https://las.inf.ethz.ch/krausea). Through co-supervised projects, I also collaborated with the [Social Networks Lab](https://sn.ethz.ch/) and the [Institute for Atmospheric and Climate Science](https://iac.ethz.ch/).

  Before my PhD, I studied at École Polytechnique (computer science & mathematics) and completed a Master's degree in Environmental Sciences at ETH Zürich.

  In parallel, I contributed to several applied research projects:

  - Microsoft Research Cambridge (2022): explainability for molecular prediction
  - Meta AI Paris (2021): improving decoder architectures for compression retrieval
  - Crowther Lab, ETH (2020): species detection with GNNs and optimal transport
  - Earth Institute, Columbia University (2019): wildfire prediction
  - DAIKIN Osaka (2018): software engineering
  - IFCEN Zhuhai (2017): full-time teaching assistant for 6 months
  </div>
  <div class="col-md-4 m-auto" style="text-align: center">
    <img class="img-responsive rounded-circle profile" src="assets/img/{{page.profile.image}}">
  </div>
</div>

## News

{% if page.news %}
{% include news.html %}
{% endif %}
