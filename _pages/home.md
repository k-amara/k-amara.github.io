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
  I am an ETH AI Center Doctoral Fellow. My research interest is on Explainability for Graph Neural Networks, and its use for atmospheric and climate models, banks, and the e-​commerce. I am particularly interested in 
  - the fundamental ideas of deep learning on graphs, neural network interpretability, network analysis as well as graph theory and reinforcement learning
  - applications in environmental sciences and social networks. 
  
  I am part of the DS3Lab ([Institute for Computing Platforms - Systems Group](https://systems.ethz.ch/)) led by Prof. [Ce Zhang](https://systems.ethz.ch/people/profile.ce-zhang.html), the [Social Networks Lab](https://sn.ethz.ch/) led by Prof. [Ulrik Brandes](https://sn.ethz.ch/profile.html?persid=239462) and the IAC ([Institute for Atmospheric and Climate Science](https://iac.ethz.ch/)) led by Prof. [Sebastian Schemm](https://usys.ethz.ch/en/people/profile.MTU3ODEz.TGlzdC8yODUyLDMyMDE5NzIyMg==.html).

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
