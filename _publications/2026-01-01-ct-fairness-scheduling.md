---
title: "Optimizing Multi-Stakeholder Fairness in Computed Tomography Appointment Scheduling with Predicted Scan and Reporting Duration"
collection: publications
permalink: /publication/2026-ct-fairness-scheduling
excerpt: 'A predictive-prescriptive framework combining machine learning and multi-objective optimization for fairness-aware follow-up CT scheduling.'
date: 2026-06-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2608.13059'
status: preprint
---

Scheduling follow-up Computed Tomography (CT) examinations requires balancing two competing objectives: assigning patients as close as possible to their clinically recommended examination dates while ensuring an equitable distribution of radiologists’ reporting workload. Existing approaches largely optimize scanner utilization or patient waiting times, overlooking both reporting activities and the need to balance fairness across multiple stakeholders. Moreover, the practical value of Machine Learning (ML) predictions depends on their integration into prescriptive decision-support models.
This paper proposes a predictive-prescriptive framework for fairness-aware follow-up CT scheduling. Patient-specific ML models are first developed to predict both examination and reporting durations. These predictions are then embedded into a multi-objective Mixed-Integer Linear Programming (MILP) model that simultaneously minimizes deviations from patients’ preferred examination dates and balances radiologists’ reporting workloads through a lexicographic min-max fairness criterion. To efficiently characterize the trade-offs between these conflicting objectives, we derive a dominance reduction property within an $\varepsilon$-constraint framework that substantially reduces the number of optimization problems required to generate the Pareto frontier.
Computational experiments based on data from a real-world emergency radiology department show that allowing patients a scheduling flexibility of only one to two days is sufficient to substantially improve workload equity among radiologists while preserving timely access to follow-up examinations. The proposed dominance reduction strategy eliminates most $\varepsilon$-constraint evaluations without affecting the Pareto frontier. Finally, evaluating predictive models through downstream optimization regret demonstrates that XGBoost provides the most effective support for scheduling decisions, outperforming models that achieve lower prediction errors according to conventional predictive metrics.
