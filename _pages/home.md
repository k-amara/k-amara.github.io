---
layout: page
permalink: /
title: Home
description: ETH AI Center Doctoral Fellow. Studied at École polytechnique and ETH Zürich.

profile:
  image: avatar.jpg
  address: >

nav: false
news: true # includes a list of news items
---

## About me

<div class="row">
  <div class="col-md-8" markdown="1"> 
  I am an ETH AI Center Doctoral Fellow ([ETH AI Center](https://ai.ethz.ch/)). 
  My research interest is on explainability for language models, graph neural networks and transformer-based architectures, and its use for health and climate models. 
  I am particularly interested in:
  - LLM explainability (model-agnostic post-hoc xAI methods, evaluation, linguistic perturbations)
  - Deep learning on graphs, GNN explainability, network analysis, graph theory. 
  - Multimodal explainability (image, text, graph).
  - Generative AI for drug discovery.
  - Applications in health, environmental sciences and social networks. 
  
  I am part of the [ETH AI Center](https://ai.ethz.ch/) and [IVIA lab](https://ivia.ethz.ch/) led by Prof. [Mennatallah El-Assady](https://el-assady.com/)
  In the context of my co-supervisions, I work closely with the [Social Networks Lab](https://sn.ethz.ch/) led by Prof. [Ulrik Brandes](https://sn.ethz.ch/profile.html?persid=239462) and the IAC ([Institute for Atmospheric and Climate Science](https://iac.ethz.ch/)) led by Prof. [Sebastian Schemm](https://usys.ethz.ch/en/people/profile.MTU3ODEz.TGlzdC8yODUyLDMyMDE5NzIyMg==.html).

Prior to my PhD, I studied at École polytechnique, majoring in computer science and mathematics. I also hold a Master's degree from ETH Zürich in environmental sciences and policy.

  </div>
  <div class="col-md-4 m-auto" style="text-align: center">
    <img class="img-responsive rounded-circle profile" src="assets/img/{{page.profile.image}}">
  </div>
</div>

## News

{% if page.news %}
{% include news.html %}
{% endif %}
