---
title: "IndiCon: Selecting SAT Encodings for Individual Pseudo-Boolean and Linear Integer Constraints"
collection: publications
permalink: /publication/2024-10-30-indicon-ictai
excerpt: >
  Learning to select SAT encodings for individual constraints in a CSP instance.
date: 2024-10-28
venue: >
  Proceedings of the 36th International Conference on Tools with Artificial Intelligence (ICTAI
  2024)
citation: >
  Felix Ulrich-Oltean, Peter Nightingale, James A. Walker, "IndiCon: Selecting SAT Encodings for
  Individual Pseudo-Boolean and Linear Integer Constraints", Proceedings of the 36th International
  Conference on Tools with Artificial Intelligence (ICTAI 2024)
paperurl: https://pure.york.ac.uk/portal/en/publications/indicon-selecting-sat-encodings-for-individual-pseudo-boolean-and
---

Encoding to SAT and applying a state-of-the-art SAT solver can be a highly effective way of solving
constraint problems. For many types of constraints there exist several alternative SAT encodings;
and the choice of encoding can significantly affect SAT solver performance for any given
problem. Previous work has shown that machine learning (ML) can be used to select SAT encodings for
some constraint types, making a choice for each relevant constraint type in a problem instance. The
state-of-the-art approach achieves good performance by first building a small portfolio of
configurations, then selecting a configuration for a given problem instance using an ML model. The
approach necessitates generating training data for every combination of encodings for the constraint
types, thus it scales exponentially as more constraint types are added. In this work, we select
potentially different encodings for each individual constraint in a problem instance. We are able to
match the state-of-the-art performance while avoiding any limitation on the number of constraint
types considered. To achieve this we are proposing new individual constraint features, we present a
novel method for generating training data, and we have developed a new machine learning pipeline
involving both unsupervised and supervised learning.
