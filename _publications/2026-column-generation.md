---
title: "Integrated Surgical Scheduling with Weekend Bed Occupancy Management: A Column Generation Approach"
collection: publications
permalink: /publication/2026-column-generation
excerpt: 'A joint optimization framework for surgical scheduling under weekend bed capacity constraints, combining a multi-criteria MILP with a Column Generation algorithm to balance patient access and OR utilization.'
date: 2026-01-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2608.11018'
status: preprint
---

This paper addresses the integrated Master Surgical Scheduling Problem and Surgical Case Assignment Problem under weekend bed capacity constraints. We propose a joint optimization framework that simultaneously determines the assignment of specialties and surgeons to Operating Room (OR) blocks, the selection and assignment of patients to these blocks, and the sequencing of surgeries, while accounting for reduced bed availability during weekends. The model is formulated as a multi-criteria Mixed-Integer Linear Program (MILP) that prioritizes the total priority-weighted amount of scheduled patients, minimizes excess weekend bed occupancy, and maximizes OR utilization. To solve large instances, we develop a Column Generation (CG) algorithm in which the pricing subproblem is formulated as a Resource-Constrained Shortest Path Problem. The framework accommodates block, open, and modified block scheduling policies. Computational experiments show that the CG approach outperforms the direct MILP solution in terms of solution quality and computational time, particularly for larger instances. We further analyze the trade-offs between weekend bed availability, OR utilization, and total patient priority. Our results provide managerial insights into how hospitals can balance patient access, operational efficiency, and staff workload when resources are limited.
