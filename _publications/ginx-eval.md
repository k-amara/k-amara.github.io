---
layout: publication_page
show: true
noheader: true

title: "GInX-Eval: Towards In-Distribution Evaluation of Graph Neural Network Explanations"
description:

date: 2023-12-09

authors:
  - name: <b>Kenza Amara</b>
    url: "https://k-amara.github.io/"
    affiliations: [ETH AI Center]
  - name: Mennatallah El-Assady
    url: "https://el-assady.com/"
    affiliations: [ETH Zürich]
  - name: Rex Ying
    url: "https://www.cs.yale.edu/homes/ying-rex/"
    affiliations: [Yale University]

bib: /assets/bibliography/ginx-eval.txt
abstract: In this paper, we show the limitations of faithfulness metrics. We propose GInX-Eval (Graph In-distribution eXplanation Evaluation), an evaluation procedure of graph explanations that overcomes the pitfalls of faithfulness and offers new insights on explainability methods. Using a fine-tuning strategy, the GInX score measures how informative removed edges are for the model and the HomophilicRank score evaluates if explanatory edges are correctly ordered by their importance and the explainer accounts for redundant information. GInX-Eval verifies if ground-truth explanations are instructive to the GNN model. In addition, it shows that many popular methods, including gradient-based methods, produce explanations that are not better than a random designation of edges as important subgraphs, challenging the findings of current works in the area. Results with GInX-Eval are consistent across multiple datasets and align with human evaluation.
pdf: /assets/pdf/ginx-eval.pdf
url: https://openreview.net/pdf?id=w6Qnoy2RXG

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
