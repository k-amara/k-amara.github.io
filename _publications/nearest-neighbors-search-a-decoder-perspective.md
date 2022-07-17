---
layout: publication_page
show: true
noheader: true

title: "Nearest neighbor search with compact codes: A decoder perspective"
description: 

date: 2021-12-27

authors:
  - name: <b>Kenza Amara</b>
    url: "https://k-amara.github.io/"
    affiliations: [Meta AI]
  - name: Matthijs Douze
    url: "https://scholar.google.com/citations?user=0eFZtREAAAAJ&hl=en"
    affiliations: [Meta AI]
  - name: Alexandre Sablayrolles
    url: "https://alexandresablayrolles.github.io/"
    affiliations: [Meta AI]
  - name: Hervé Jégou
    url: "https://scholar.google.com/citations?user=1lcY2z4AAAAJ&hl=en"
    affiliations: [Meta AI]

journal: ArXiv
bib: /assets/bibliography/nearest-neighbors-search-a-decoder-perspective.txt
abstract: Modern approaches for fast retrieval of similar vectors on billion-scaled datasets rely on compressed-domain approaches such as binary sketches or product quantization. These methods minimize a certain loss, typically the mean squared error or other objective functions tailored to the retrieval problem. In this paper, we re-interpret popular methods such as binary hashing or product quantizers as auto-encoders, and point out that they implicitly make suboptimal assumptions on the form of the decoder. We design backward-compatible decoders that improve the reconstruction of the vectors from the same codes, which translates to a better performance in nearest neighbor search. Our method significantly improves over binary hashing methods or product quantization on popular benchmarks.
pdf: /assets/pdf/nearest-neighbors-search-a-decoder-perspective.pdf
arxiv: https://arxiv.org/abs/2112.09568
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