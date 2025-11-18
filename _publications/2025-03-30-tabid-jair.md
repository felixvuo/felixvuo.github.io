---
title: "TabID: Automatic Identification and Tabulation of Subproblems in Constraint Models"
collection: publications
permalink: /publication/2025-03-30-tabid-jair
excerpt: >
  One of the first papers I was able to contribute to during my PhD, conducting
  extensive experiments, and presenting complex results concisely.
date: 2025-03-30
venue: 'Journal of Artificial Intelligence Research'
paperurl: https://doi.org/10.1613/jair.1.17032
citation: >
  Akgün, Özgür, Ian Gent, Christopher Jefferson, Zeynep Kiziltan, Ian Miguel,
  Peter Nightingale, András Salamon, and Felix Ulrich-Oltean. "TabID: automatic
  identification and tabulation of subproblems in constraint models." Journal of
  Artificial Intelligence Research 82 (2025): 1999-2056.
---

The performance of a constraint model can often be improved by converting a
subproblem into a single table constraint (referred to as tabulation). This
paper presents TabID, an entirely automated method to identify promising
subproblems for tabulation in constraint programming. We introduce a diverse set
of heuristics designed to identify promising candidates for tabulation, aiming
to improve solver performance. These heuristics are intended to encapsulate
various factors that contribute to useful tabulation. We also present additional
checks to limit the potential drawbacks of suboptimal tabulation.  We
comprehensively evaluate our approach using benchmark problems from existing
literature that previously relied on manual identification by constraint
programming experts of constraints to tabulate. We demonstrate that our
automated identification and tabulation process achieves comparable, and in some
cases improved results. We empirically evaluate the efficacy of our approach on
a variety of solvers, including standard CP (Minion and Gecode), clause-learning
CP (Chuffed and OR-Tools) and SAT solvers (Kissat).  Our findings highlight the
substantial potential of fully automated tabulation, suggesting its integration
into automated model reformulation tools.

