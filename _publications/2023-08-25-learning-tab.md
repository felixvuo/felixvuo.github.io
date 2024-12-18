---
title: "Learning When to Use Automatic Tabulation in Constraint Model Reformulation"
collection: publications
permalink: /publication/2023-08-25-learning-tab
excerpt: >
  Using ML strategies to decide whether to reformulate parts of constraint
  models as table constraints.
date: 2023-08-25
venue: >
  Proceedings of the Thirty-Second International Joint Conference on Artificial
  Intelligence
paperurl: https://doi.org/10.24963/ijcai.2023/211
citation: >
  Carlo Cena, Özgür Akgün, Zeynep Kiziltan, Ian Miguel, Peter Nightingale, Felix
  Ulrich-Oltean, "Learning When to Use Automatic Tabulation in Constraint Model
  Reformulation", Proceedings of the Thirty-Second International Joint
  Conference on Artificial Intelligence Main Track. Pages 1902-1910.
---

Combinatorial optimisation has numerous practical applications, such as
planning, logistics, or circuit design. Problems such as these can be solved by
approaches such as Boolean Satisfiability (SAT) or Constraint Programming
(CP). Solver performance is affected significantly by the model chosen to
represent a given problem, which has led to the study of model
reformulation. One such method is tabulation: rewriting the expression of some
of the model constraints in terms of a single table constraint. Successfully
applying this process means identifying expressions amenable to trans-
formation, which has typically been done manually. Recent work introduced an
automatic tabulation using a set of hand-designed heuristics to identify
constraints to tabulate. However, the performance of these heuristics varies
across problem classes and solvers. Recent work has shown learning techniques to
be increasingly useful in the context of automatic model reformulation. The goal
of this study is to understand whether it is possible to improve the performance
of such heuristics, by learning a model to predict whether or not to activate
them for a given instance. Experimental results suggest that a random forest
classifier is the most robust choice, improving the performance of four
different SAT and CP solvers.
