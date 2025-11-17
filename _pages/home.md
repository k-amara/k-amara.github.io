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

    I recently completed my PhD as a Doctoral Fellow at the [ETH AI Center](https://ai.ethz.ch/), where I worked at the intersection of explainability, multimodal learning, and graph-based deep learning. My research focuses on developing transparent and interpretable methods for large language models, graph neural networks, and transformer architectures, with applications in health, climate science, and environmental systems.

    My main interests include:
    
    - LLM explainability — model-agnostic XAI, post-hoc evaluation, linguistic perturbations
    
    - Deep learning on graphs — GNN explainability, network analysis, graph theory
    
    - Multimodal explainability — image, text, graph representations
    
    - Generative AI for molecular design and drug discovery
    
    - Applications in health, climate, and social networks
    
    During my PhD, I was part of the [IVIA Lab](https://ivia.ethz.ch/), led by Prof. Mennatallah El-Assady, and collaborated closely with the [Social Networks Lab](https://sn.ethz.ch/) (Prof. Ulrik Brandes) and the [Institute for Atmospheric and Climate Science](https://iac.ethz.ch/) (Prof. Sebastian Schemm). These collaborations allowed me to bridge AI research with real-world domains such as climate modelling, network science, and observational data analysis.
    
    Before joining the ETH AI Center, I studied computer science and applied mathematics at École Polytechnique, and completed a second master’s degree in environmental sciences and policy at ETH Zürich.
    
    Alongside my academic work, I have completed several research internships across industry and academia:
    
    - Microsoft Research Cambridge (2022) — improving feature attribution methods for molecular prediction in drug discovery
    
    - Meta AI Paris (2021) — enhancing decoder capacity for retrieval and compression systems
    
    - Crowther Lab, ETH Zurich (2020) — developing OneForest, a GNN-based tree species detection algorithm using optimal transport
    
    - Earth Institute, Columbia University (2019) — machine-learning prediction of Californian wildfires
    
    Earlier in my career, I worked as a Software Engineering intern at DAIKIN in Osaka, Japan (2018), and spent six months as a full-time Teaching Assistant at the Sino-French Institute of Nuclear Engineering (IFCEN) in Zhuhai, China (2017).
  
  </div>
  <div class="col-md-4 m-auto" style="text-align: center">
    <img class="img-responsive rounded-circle profile" src="assets/img/{{page.profile.image}}">
  </div>
</div>

## News

{% if page.news %}
{% include news.html %}
{% endif %}
