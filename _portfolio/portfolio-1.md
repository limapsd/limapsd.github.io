---
title: "Working Papers"
excerpt: "Minnesota Bart (with Carlos Carvalho, Hedibert Lopes and Andrew Herren)"
collection: portfolio
venue: "arXiv"
paperurl: "https://arxiv.org/abs/2503.13759"
---

Vector autoregression (VAR) models are widely used for forecasting and macroeconomic analysis, yet they remain limited by their reliance on a linear parameterization. Recent research has introduced nonparametric alternatives, such as Bayesian additive regression trees (BART), which provide flexibility without strong parametric assumptions. However, existing BART-based frameworks do not account for time dependency or allow for sparse estimation in the construction of regression tree priors, leading to noisy and inefficient high-dimensional representations. This paper introduces a sparsity-inducing Dirichlet hyperprior on the regression tree's splitting probabilities, allowing for automatic variable selection and high-dimensional VARs. Additionally, we propose a structured shrinkage prior that decreases the probability of splitting on higher-order lags, aligning with the Minnesota prior's principles. Empirical results demonstrate that our approach improves predictive accuracy over the baseline BART prior and Bayesian VAR (BVAR), particularly in capturing time-dependent relationships and enhancing density forecasts. These findings highlight the potential of developing domain-specific nonparametric methods in macroeconomic forecasting.