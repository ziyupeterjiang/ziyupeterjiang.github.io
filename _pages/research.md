---
title: "Research"
layout: single
classes: wide
permalink: /research/
excerpt: "Working papers and research projects by Ziyu (Peter) Jiang"
author_profile: false
---

My research develops econometric tools for settings where standard identification or inference arguments are strained by high-dimensional, non-Gaussian, or unstructured data. Drafts without public links are available upon request.

## Working Papers

<article class="paper-card paper-card--featured">
  <h3>Identification and Estimation of Simultaneous Equation Models Using Higher-Order Cumulant Restrictions</h3>

  <p class="paper-meta">
    <strong>Status:</strong> Revise and resubmit, <em>Journal of Econometrics</em><br>
    <strong>Public version:</strong> arXiv working paper, 2025
  </p>

  <p class="paper-links">
    <a href="https://arxiv.org/abs/2501.06777" class="btn btn--primary btn--small">arXiv</a>
  </p>

  <p><strong>Abstract.</strong> Identifying structural parameters in linear simultaneous-equation models is a longstanding challenge. Recent work exploits information in higher-order moments of non-Gaussian data. In this literature, structural errors are typically assumed to be uncorrelated so that, after standardizing the covariance matrix of the observables, the structural parameter matrix becomes orthogonal. This paper shows that neither zero covariance nor whitening is necessary. For any order greater than two, a simple diagonality condition on higher-order cumulants identifies the structural parameter matrix, up to unknown scaling and permutation, through an eigenvector problem. The result yields a sample-analogue estimator that is root-n consistent, asymptotically normal, and straightforward to compute. When uncorrelatedness is intrinsic, as in vector autoregressive models, the framework also provides an overidentification test. Monte Carlo experiments show favorable finite-sample performance, and applications to returns to schooling and uncertainty and the business cycle illustrate its practical value.</p>
</article>

<article class="paper-card">
  <h3>Moment-Based Inference for Regression with Latent Dirichlet Covariates</h3>

  <p class="paper-meta">
    <strong>Status:</strong> Working paper<br>
    <strong>Public version:</strong> arXiv working paper, 2026
  </p>

  <p class="paper-links">
    <a href="https://arxiv.org/abs/2605.30718" class="btn btn--primary btn--small">arXiv</a>
  </p>

  <p><strong>Abstract.</strong> Topic models are often used as dimension-reduction tools before regression, where estimated document-level topic shares are treated as observed covariates. This creates inference problems because topic-estimation uncertainty must be propagated into the second stage, and with fixed document length a document's topic mixture is not consistently recoverable from its own words. Building on corrected spectral moment methods for latent Dirichlet allocation, this paper develops a supervised moment approach for downstream regression. Under a finite LDA model, response-weighted word moments can be corrected so that a supervised operator identifies the regression coefficient directly, without estimating document-level topic shares. The main complication is that the correction depends on the unknown total Dirichlet concentration. I show that, for at least three topics and under a generic finite-probe condition, this concentration is identified through a commutativity restriction among corrected operators. The resulting estimator is asymptotically linear as the number of documents grows with fixed document length, admits sandwich standard errors, improves coverage relative to plug-in topic-share regressions in simulations, and is applied to latent topic effects in top economics journals.</p>
</article>

## Work in Progress

<article class="paper-card">
  <h3>Micro-foundation for Topic Models</h3>

  <p class="paper-meta">
    <strong>Status:</strong> Work in progress
  </p>
</article>

<!-- When you are on the job market, add a separate "Job Market Paper" heading above the relevant paper and place it first. -->
