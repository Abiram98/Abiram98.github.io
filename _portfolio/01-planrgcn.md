---
title: "PlanRGCN and PlanRGCN+"
excerpt: "Graph neural networks for predicting database query performance from graph-based query representations."
collection: portfolio
permalink: /projects/planrgcn/
---

<p class="project-meta">Graph neural networks · Query performance prediction · PyTorch · DGL</p>

PlanRGCN addresses query performance prediction for SPARQL workloads: estimating execution behaviour before a query is run. The project turns complex query structures and historical workloads into a predictive component that can support operational database decisions.

## Contribution

- Built Python pipelines to extract, clean, and process real-world SPARQL query logs.
- Constructed reproducible datasets from DBpedia and Wikidata workloads, including graph-based query representations and domain-specific features.
- Designed and evaluated relational graph convolutional models with PyTorch and Deep Graph Library (DGL).
- Investigated class imbalance, generalization, architectural alternatives, and model adaptation.
- Integrated predictions with downstream execution-control and load-balancing applications.

## Result

The original PlanRGCN evaluation demonstrated up to **207% higher throughput** in a load-balancing setting. PlanRGCN+ is an ongoing journal extension; it is not yet published.

## Links

- [Source code](https://github.com/dkw-aau/PlanRGCN)
- [Publication: PlanRGCN: Predicting SPARQL Query Performance](https://doi.org/10.14778/3725688.3725694)
