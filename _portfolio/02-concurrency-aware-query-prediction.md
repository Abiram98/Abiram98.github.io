---
title: "Concurrency-Aware Query Prediction"
excerpt: "Predictive models and execution control that account for interference among concurrently running database queries."
collection: portfolio
permalink: /projects/concurrency-aware-query-prediction/
---

<p class="project-meta">Sequence models · Workload management · Scheduling · Experimental systems</p>

Concurrent database queries can interfere with one another, making a query's isolated execution time a poor guide for operational decisions. This ongoing research develops predictive models and scheduling mechanisms that take the active workload into account.

## Contribution

- Developed LSTM-based models that combine learned query representations with concurrent workload information.
- Designed runtime-prediction-based scheduling and execution-control policies.
- Built experiment pipelines to generate concurrent workloads and evaluate scheduling strategies.
- Integrated prediction models with an operational database system.
- Analyzed latency distributions, throughput, timeouts, and scheduling trade-offs.

## Result

In evaluated configurations, execution control reduced time spent on unsuccessful queries by up to **75.9%** without reducing the query success rate.

## Status

Ongoing research. No publication link is listed because this work is not represented as accepted or published.
