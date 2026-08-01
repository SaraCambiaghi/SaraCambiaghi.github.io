---
title: "Multi-objective outpatient scheduling via learning-based adaptive evolutionary search"
collection: publications
category: manuscripts
permalink: /publication/2026-outpatient-scheduling-nsga2
excerpt: 'A learning-based adaptive evolutionary approach for outpatient scheduling that leverages historical solutions to improve future schedules.'
date: 2026-01-01
venue: 'Computers & Operations Research'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0305054826002157'
citation: 'S. Cambiaghi, D. Duma, Multi-objective outpatient scheduling via learning-based adaptive evolutionary search, Computers & Operations Research 194 (2026) 107597. doi:https://doi.org/10.1016/j.cor.2026.107597.'
status: published
---

Outpatient Appointment Scheduling (OAS) often involves repeatedly solving multi-objective optimization problems that differ in their waiting lists but share structural similarities across planning periods. In traditional operations research approaches, instances of computationally complex OAS problems are solved from scratch using metaheuristics, overlooking valuable knowledge embedded in past solutions. In this work, we introduce a learning-based adaptive evolutionary approach that leverages historical solutions to improve the effectiveness of future schedules within a fixed computational budget. As a case study, we address a real-world OAS problem for CT-scan scheduling in emergency departments, where three patient categories (outpatients, inpatients, and emergencies) compete for limited resources. We formulate the problem as a multi-objective stochastic program aiming to minimize outpatient waiting times and inpatient and emergency completion times. To solve it, we use the Non-dominated Sorting Genetic Algorithm II (NSGA-II), enhanced with an adaptive warm-start strategy based on a weighted K-Nearest Neighbors method that incorporates a prediction model and optimal assignment to identify the most similar historical instances. Pareto approximations already computed for these instances allow for a similarity-weighted bootstrapping mechanism that generates a tailored initial population. The proposed approach is evaluated in different operational contexts using real-world data from a regional trauma hub in Pavia, Italy.
