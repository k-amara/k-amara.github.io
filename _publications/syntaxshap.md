---
layout: publication_page
show: true
noheader: true

title: "SyntaxShap: Syntax-aware Explainability Method for Text Generation"
description:

date: 2024-02-15

authors:
  - name: <b>Kenza Amara</b>
    url: "https://k-amara.github.io/"
    affiliations: [ETH AI Center]
  - name: Rita Sevastjanova
    affiliations: [ETH Zürich]
  - name: Mennatallah El-Assady
    url: "https://el-assady.com/"
    affiliations: [ETH Zürich]

abstract: To harness the power of large language models
in safety-critical domains we need to ensure
the explainability of their predictions. However, despite the significant attention to model
interpretability, there remains an unexplored domain in explaining sequence-to-sequence tasks
using methods tailored for textual data. This
paper introduces SyntaxShap, a local, modelagnostic explainability method for text generation that takes into consideration the syntax
in the text data. The presented work extends
Shapley values to account for parsing-based
syntactic dependencies. Taking a game theoric approach, SyntaxShap only considers coalitions constraint by the dependency tree. We
adopt a model-based evaluation to compare
SyntaxShap and its weighted form to state-ofthe-art explainability methods adapted to text
generation tasks, using diverse metrics including faithfulness, complexity, coherency, and
semantic alignment of the explanations to the
model. We show that our syntax-aware method
produces explanations that help build more
faithful, coherent, and interpretable explanations for predictions by autoregressive models.
pdf: /assets/pdf/syntaxshap.pdf
url: https://arxiv.org/pdf/2402.09259.pdf


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
