---
title: "Scheduling Telescope Observations for the European Southern Observatory"
collection: publications
permalink: /publication/2025-08-14-telescopes
excerpt: >
  Fascinating application of constraint programming to scheduling scientific observation on an array
  of telescopes which could be rearranged according to complex constraints.
date: 2025-08-14
venue: "31st International Conference on Principles and Practice of Constraint Programming (CP 2025)"
paperurl: https://doi.org/10.4230/LIPIcs.CP.2025.43
citation: >
  Michael Prümm, Peter Nightingale, Felix Ulrich-Oltean, "Scheduling Telescope
  Observations for the European Southern Observatory", 31st International
  Conference on Principles and Practice of Constraint Programming (CP 2025)
---

The European Southern Observatory (ESO) provides state-of-the-art large
telescope facilities at three sites in Chile, supported by 16 European member
states. Astronomers submit proposals for sets of observations which are reviewed
and ranked based on scientific merit, then a schedule is constructed respecting
the ranking and aiming to make the fullest use of the various telescopes and
numerous instruments. Currently a schedule covers six months, but in the near
future ESO will switch to annual schedules.

Here we examine the most challenging scheduling problem encountered by ESO:
scheduling the operations of the Very Large Telescope Interferometer (VLTI) on
Paranal, Chile. Tasks to be scheduled include observations performed by ESO
staff, "visitor mode" periods where astronomers visit the site to use the
telescopes, various maintenance tasks, and reconfiguration tasks taking multiple
days. Typically a VLTI six-month schedule would contain approximately 450
activities. We explore global constraint models and a SAT encoding of the
problem.
