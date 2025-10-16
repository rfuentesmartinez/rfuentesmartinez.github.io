---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---


## Working papers

- _"Expected shortfall estimation with Stationary vine copulas"_ with Juan Mora

  We assess the performance of Stationary Vine Copula models (S-vines) for estimating the Expected Shortfall (ES) of the returns from a portfolio of financial assets. For this purpose, we propose an estimation procedure based    in the Monte Carlo method using S-vines, for estimating the _k_-periods ahead ES of a financial portfolio at a given time period _t_, employing a rolling window approach. Notably, by means of a simulation study we find         evidence that, under some scenarios of dependence, the S-vine ES estimates outperform those from models commonly used in financial time series modeling, while having a relatively similar performance under other data            generating processes. Finally, through an empirical application we show that using the S-vines ES estimates in the context of portfolio optimization can lead to better strategies than other models that consider serial          dependence and cross-sectional dependence individually, in particular, when working with large portfolios.

- _"Non-linear dependence and Granger causality: a vine copula approach"_ with Irene Crimaldi and Armando Rungi (submitted as a book chapter in the Springer series “Contributions to Statistics”)

  Inspired by Jang et al. (2022), we propose a Granger causality-in-the-mean test for bivariate _k_−Markov stationary processes based on a recently introduced class of non-linear models, i.e., vine copula models. By means of a   simulation study, we show that the proposed test improves on the statistical properties of the original test in Jang et al. (2022), and also of other previous methods, constituting an excellent tool for testing Granger         causality in the presence of non-linear dependence structures. Finally, we apply our test to study the pairwise relationships between energy consumption, GDP and investment in the U.S. and, notably, we find that Granger-       causality runs two ways between GDP and energy consumption.

## Work in progress

- _"Enhancing portfolio performances through option-implied informations"_ with Antonio Rubia and Carlo Sala



{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

