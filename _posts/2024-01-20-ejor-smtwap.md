---
title: 'SMTWAP on European Journal of Operational Research'
date: 2024-01-20
permalink: /posts/2024/01/ejor-smtwap/
tags:
  - routing
  - time windows
  - stochastic programming
  - meta-heuristics
  - publications
---

Finally, the article written together with Jean-François Côté and Renata Mansini, and born initially from my master's thesis developed at the Université Laval in Québec City, has been accepted and published in the European Journal of Operational Research.

If you are interested in time windows assignment, two-stage stochastic programs, and meta-heuristics, our article is available [online](https://doi.org/10.1016/j.ejor.2024.01.021) with 50 days of free access.

In this work, we study a multi-period stochastic variant of the Time Window Assignment Vehicle Routing Problem, where customers’ demands, locations, and service times are uncertain. Customers are partitioned into geographical zones, each of which has to be visited a predetermined number of times over a planning period of several days. Whenever a zone is visited, a time window is assigned. Time windows are decided before knowing customers and their demands. A fleet of homogeneous vehicles is available to serve customers each day. At a tactical level, the problem looks for a static time window assignment that minimizes the expected traveling costs plus the expected penalty costs for unserved customers.

We propose a two-stage formulation and a solution approach, which relies on the Sample Average Approximation Method, while encompassing a perturbation method to assign time windows in the first stage and an Adaptive Large Neighborhood Search to optimize routes in the second stage. We experimentally evaluate three instance sets, including real ones from a Canadian company, comparing our results to lower bounds from the exact solution of a deterministic equivalent formulation over a finite number of scenarios. Our method outperforms the manual approach used by the company.
