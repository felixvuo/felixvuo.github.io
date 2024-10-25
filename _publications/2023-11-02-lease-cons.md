---
title: "Learning to select SAT encodings for pseudo-Boolean and linear integer constraints"
collection: publications
permalink: /publication/2023-11-02
excerpt: "Extended journal version of the work in the first two technical chapters of my PhD thesis"
date: 2021-11-02
venue: "Constraints"
paperurl: https://doi.org/10.1007/s10601-023-09364-1
citation: >
  Felix Ulrich-Oltean, Peter Nightingale & James A. Walker, "Learning to select
  SAT encodings for pseudo-Boolean and linear integer constraints". Constraints
  28, 397–426 (2023).
---

Many constraint satisfaction and optimisation problems can be solved effectively
by encoding them as instances of the Boolean Satisfiability problem
(SAT). However, even the simplest types of constraints have many encodings in
the literature with widely varying performance, and the problem of selecting
suitable encodings for a given problem instance is not trivial. We explore the
problem of selecting encodings for pseudo-Boolean and linear constraints using a
supervised machine learning approach. We show that it is possible to select
encodings effectively using a standard set of features for constraint problems;
however we obtain better performance with a new set of features specifically
designed for the pseudo-Boolean and linear constraints. In fact, we achieve good
results when selecting encodings for unseen problem classes. Our results compare
favourably to AutoFolio when using the same feature set. We discuss the relative
importance of instance features to the task of selecting the best encodings, and
compare several variations of the machine learning method.
