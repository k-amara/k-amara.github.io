---
layout: publication_page
show: true
noheader: true

title: "GraphFramEx: Towards Systematic Evaluation of
Explainability Methods for Graph Neural Networks"
description: 

date: 2022-06-09

authors:
  - name: <b>Kenza Amara</b>
    url: "https://k-amara.github.io/"
    affiliations: [ETH AI Center]
  - name: Rex Ying
    url: "https://cs.stanford.edu/people/rexy/"
    affiliations: [Stanford]
  - name: Ce Zhang
    url: "https://ds3lab.inf.ethz.ch/members/ce-zhang.html"
    affiliations: [ETH Zürich]

journal: ArXiv
bib: /assets/bibliography/graphframex-towards-systematic-evaluation-of-explainability-methods-for-graph-neural-networks.txt
abstract: As one of the most popular machine learning models today, graph neural networks
(GNNs) have attracted intense interest recently, and so does their explainability.
Users are increasingly interested in a better understanding of GNN models and their
outcomes. Unfortunately, today's evaluation frameworks for GNN explainability
often rely on synthetic datasets, leading to conclusions of limited scope due to
a lack of complexity in the problem instances. As GNN models are deployed to
more mission-critical applications, we are in dire need for a common evaluation
protocol of explainability methods of GNNs. In this paper, we propose, to our
best knowledge, the first systematic evaluation framework for GNN explainability,
considering explainability on three different “user needs:” explanation focus, mask
nature, and mask transformation. We propose a unique metric that combines the
fidelity measures and classify explanations based on their quality of being sufficient
or necessary. We scope ourselves to node classification tasks and compare the most
representative techniques in the field of input-level explainability for GNNs. For
the widely used synthetic benchmarks, surprisingly shallow techniques such as
personalized PageRank have the best performance for a minimum computation
time. But when the graph structure is more complex and nodes have meaningful
features, gradient-based methods, in particular Saliency, are the best according
to our evaluation criteria. However, none dominates the others on all evaluation
dimensions and there is always a trade-off. We further apply our evaluation protocol
in a case study on eBay graphs to reflect the production environment.
pdf: /assets/pdf/graphframex-towards-systematic-evaluation-of-explainability-methods-for-graph-neural-networks.pdf
arxiv: https://arxiv.org/pdf/2206.09677.pdf
img: /assets/img/splash-decoder.png

# Below is an example of injecting additional page-specific styles.
# If you use this page as a template, delete this _styles block.
_styles: >
  # .fake-img {
  #   background: #bbb;
  #   border: 1px solid rgba(0, 0, 0, 0.1);
  #   box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
  #   margin-bottom: 12px;
  # }
  # .fake-img p {
  #   font-family: monospace;
  #   color: white;
  #   text-align: left;
  #   margin: 12px 0;
  #   text-align: center;
  #   font-size: 16px;
  # }
---

## Downloads

- [PDF]({{page.pdf}})
