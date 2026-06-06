---
title: "Research"
layout: single
classes: wide
permalink: /research/
excerpt: "Working papers and research projects by Ziyu (Peter) Jiang"
author_profile: false
---

My research develops econometric tools for settings where standard identification or inference arguments are strained by high-dimensional, non-Gaussian, or unstructured data. Drafts without public links are available upon request.

## Working papers

<article class="paper-card paper-card--featured">
  <h3>Identification and Estimation of Simultaneous Equation Models Using Higher-Order Cumulant Restrictions</h3>

  <p class="paper-meta">
    <strong>Status:</strong> Revise and resubmit, <em>Journal of Econometrics</em><br>
    <strong>Public version:</strong> arXiv working paper, 2025
  </p>

  <p class="paper-links">
    <a href="https://arxiv.org/abs/2501.06777" class="btn btn--primary btn--small">arXiv</a>
  </p>

  <p><strong>Abstract.</strong> Identifying structural parameters in linear simultaneous-equation models is a fundamental challenge in economics and related fields. Recent work leverages higher-order moments, exploiting the fact that non-Gaussian data contain more structural information than Gaussian data. While many of these contributions require zero covariance among structural errors, this paper shows that the assumption, and the associated pre-whitening step, can be dispensed with. Under a diagonality condition on higher-order cumulants, the structural parameter matrix can be identified by solving a simple eigenvector problem. This insight motivates a sample-analogue estimator that is root-n-consistent, asymptotically normal, and computationally straightforward. When uncorrelatedness is an essential model feature, as in vector autoregressive models, the framework also provides a transparent misspecification test based on higher-order orthogonality conditions. Monte Carlo experiments demonstrate desirable finite-sample performance, and two empirical applications illustrate the method's practical value.</p>
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

  <p><strong>Abstract.</strong> Topic models are often used as dimension-reduction tools before regression, with estimated document-level topic shares treated as observed covariates. This plug-in workflow creates two inferential difficulties: valid inference requires a regular first-stage-to-second-stage expansion that propagates topic-estimation uncertainty, and, at fixed document length, a document's topic mixture cannot be consistently recovered from its own words even when the population topic matrix is known.</p>

  <p>Corrected spectral moment methods for latent Dirichlet allocation (LDA) offer a starting point: when the total Dirichlet concentration is known, low-order word moments can be corrected to yield operators diagonal in the latent topic basis. We extend this to downstream regression.</p>

  <p>Under a finite LDA model with response residuals orthogonal to the low-order token moments used for identification, response-weighted word moments admit the same correction, and the resulting supervised operator identifies the regression coefficient \(\beta\) directly, without estimating document-level topic shares. The main obstacle is that the correction depends on the unknown total concentration \(\alpha_0\).</p>

  <p>We show that, for \(k\ge3\) topics and under a generic finite-probe condition, \(\alpha_0\) is identified by commutativity: at the true value a family of corrected word-moment operators commute, whereas away from it they generically do not. This yields a feasible estimator and lets uncertainty in \(\hat\alpha_0\) propagate into inference for \(\beta\).</p>

  <p>The estimator is asymptotically linear as the number of documents grows with fixed document length, with sandwich standard errors from document-level moment contributions. Simulations show near-nominal coverage where plug-in topic-share regressions can undercover, and an application to top economics journals illustrates contrast inference for latent topic effects.</p>
</article>

## Work in progress

<article class="paper-card">
  <h3>Micro-foundation for Topic Models</h3>

  <p class="paper-meta">
    <strong>Status:</strong> Work in progress
  </p>
</article>

<!-- When you are on the job market, add a separate "Job Market Paper" heading above the relevant paper and place it first. -->
