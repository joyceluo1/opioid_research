---
permalink: /
title: "Equitable Data-Driven Resource Allocation to Fight the Opioid Epidemic: A Mixed-Integer Optimization Approach"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Problem definition: The opioid epidemic is a crisis that has plagued the United States (US) for decades. One central issue of the epidemic is inequitable access to treatment for opioid use disorder (OUD), which puts certain populations at a higher risk of opioid overdose. 

Methods: We formulate an approach that integrates a predictive, dynamical model and a prescriptive optimization problem to find the optimal locations of opioid treatment facilities and the optimal treatment budget distribution in each US state. Our predictive model is a differential equation-based epidemiological model that captures the dynamics of the changing opioid epidemic. We use neural ordinary differential equations to fit this model to opioid epidemic data for each state and obtain estimates for unknown parameters in the model. We then integrate this epidemiological model for each state into a corresponding mixed-integer optimization problem (MIP) for treatment facility location and resource allocation. We seek to minimize opioid overdose deaths and the number of people with OUD. Our MIPs also target socioeconomic equitability by considering social vulnerability (from the CDC’s Social Vulnerability Index) and opioid prescribing rates in each county. 

Results: Overall, our approach’s proposed solutions on average decrease the number of people with OUD by 5.70 ± 0.738%, increase the number of people in treatment by 21.17 ± 3.162%, and decrease the number of opioid-related deaths by 0.51 ± 0.086% after 2 years compared to the epidemiological model’s predictions. 

Managerial implications: Rather than only evaluating the effectiveness of potential policies as in past literature, our approach is decision-focused and directly yields actionable insights for policy-makers. It provides concrete opioid treatment facility and budget allocations and quantifies the impact of these allocations on pertinent population health measures. Future iterations of this approach could be implemented as a decision-making tool to tackle the issue of opioid treatment inaccessibility.
