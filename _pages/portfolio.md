---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---

## Publications

- _"Non-linear dependence and Granger causality: a vine copula approach"_ with Irene Crimaldi and Armando Rungi (forthcoming book chapter in the Springer series "Contributions to Statistics") \[[arXiv](https://arxiv.org/abs/2409.15070)\]

  Inspired by Jang et al. (2022), we propose a Granger causality-in-the-mean test for bivariate _k_−Markov stationary processes based on a recently introduced class of non-linear models, i.e., vine copula models. By means of a simulation study, we show that the proposed test improves on the statistical properties of the original test in Jang et al. (2022), and also of other previous methods, constituting an excellent tool for testing Granger causality in the presence of non-linear dependence structures. Finally, we apply our test to study the pairwise relationships between energy consumption, GDP and investment in the U.S. and, notably, we find that Granger-causality runs two ways between GDP and energy consumption.


## Working papers

- _"Granger Causality in Expectiles: an M-vine copula test"_ with Irene Crimaldi (Submitted) \[[arXiv](https://arxiv.org/abs/2603.23294)\]

  A model-free measure of Granger causality in expectiles is proposed, generalizing the traditional mean-based measure to arbitrary positions of the conditional distribution. Expectiles are the only law-invariant risk measures that are both coherent and elicitable, making them particularly well-suited for studying distributional Granger causality where risk quantification and forecast evaluation are both relevant. Based on this measure, a test is developed using M-vine copula models that accounts for multivariate Granger causality with d+1 series under non-linear and non-Gaussian dependence, without imposing parametric assumptions on the joint distribution. Strong consistency of the test statistic is established under some regularity conditions. In finite samples, simulations show accurate size control and power increasing with sample size. A key advantage is the joint testing capability: causal relationships invisible to pairwise tests can be detected, as demonstrated both theoretically and empirically. Two applications to international stock market indices at the global and Asian regional level illustrate the practical relevance of the proposed framework.


- _"Portfolio Expected Shortfall estimation with Stationary vine copulas"_ with Juan Mora

  We assess the performance of Stationary Vine Copula models (S-vines) for estimating the Expected Shortfall (ES) of the returns from a portfolio of financial assets. For this purpose, we propose an estimation procedure based in the Monte Carlo method using S-vines, for estimating the _k_-periods ahead ES of a financial portfolio at a given time period _t_, employing a rolling window approach. Notably, by means of a simulation study we find evidence that, under some scenarios of dependence, the S-vine ES estimates outperform those from models commonly used in financial time series modeling, while having a relatively similar performance under other data generating processes. Finally, through an empirical application we show that using the S-vines ES estimates in the context of portfolio optimization can lead to better strategies than other models that consider serial dependence and cross-sectional dependence individually, in particular, when working with large portfolios.


- _"What does the option market tell us about systemic risk?"_ with Antonio Rubia and Carlo Sala

  We propose the $$\Delta\text{CoExp}$$, a forward-looking measure of systemic risk extracted from short-term option prices. Our measure replaces the quantile that the $$\Delta\text{CoVaR}$$ applies to the financial system with an expectile, the only risk measure that is both coherent and elicitable, and whose option-implied counterpart requires considerably less data to estimate. Applied to major US banks and to the US financial sector index, the $$\Delta\text{CoExp}$$ anticipates the stock-based $$\Delta\text{CoVaR}$$ by one to three weeks. We further show that standard macroeconomic and financial factors explain most of the $$\Delta\text{CoVaR}$$ but less than half of the $$\Delta\text{CoExp}$$, and that the lead stems from the component of the latter that these factors leave unexplained. These results suggest that option prices contain information on systemic risk beyond common factors, supporting the use of the $$\Delta\text{CoExp}$$ as an early-warning complement to existing measures.


{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
