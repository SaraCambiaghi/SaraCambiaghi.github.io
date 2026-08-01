---
title: "Prediction accuracy or decision quality? A predict-then-optimize perspective"
collection: publications
permalink: /publication/2026-predict-then-optimize
excerpt: 'A predict-then-optimize study for surgical scheduling comparing multiple machine learning models, showing that improved prediction accuracy does not necessarily translate into better scheduling decisions.'
date: 2026-01-01
venue: 'Shaping a Sustainable Future in the Era of Big Data, Proceedings of the 9th AIRO Young Workshop, AIRO Springer Series.'
paperurl: ''
status: accepted
---

Recent literature has increasingly explored the use of Machine Learning (ML) to predict surgical durations, under the assumption that better predictions lead to better schedules. This study investigates a predict-then-optimize approach, where several ML models (decision trees, random forests, extreme gradient boosting, categorical boosting, support vector regression, and artificial neural networks) are used to estimate surgery durations and parametrize an optimization model for surgical scheduling. The proposed model jointly addresses surgical case assignment, sequencing, timing, and surgeon allocation, aiming to minimize the cost of unscheduled patients, idle time, and overtime. Due to the computational complexity of the problem, a metaheuristic combining a constructive approach with local search is adopted. A computational analysis based on real-world operating theatre data evaluates the trade-offs between objectives. More importantly, the results reveal that improved prediction accuracy does not necessarily translate into better scheduling decisions. This highlights the need for future integrated approaches in which ML models are trained with respect to optimization outcomes rather than standard accuracy metrics.
