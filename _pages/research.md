---
title: "Research"
layout: single
classes: wide
permalink: /research/
excerpt: "Working papers and research projects by Ziyu (Peter) Jiang"
author_profile: false
---

My research connects methods from machine learning and computer science with econometric analysis. I develop methods for measuring economic concepts and studying economic relationships, with a focus on identification, estimation, and valid statistical inference.

Drafts without public links are available upon request.

## Job Market Paper

<article class="paper-card paper-card--featured">
  <h3>Subjective Annotation Studies: Valid Inference and Annotation Design</h3>

  <p><strong>Abstract.</strong> We develop a statistical framework for annotation studies of inherently subjective features of unstructured data. In the absence of a conventional ground-truth measurement, we define document-level measurements relative to a reference population of annotators whose responses are relevant to the underlying economic question. Our goal is valid inference for economic parameters which can be written as weighted averages of these measurements and smooth functions of such weighted averages. We develop an annotation design and establish asymptotically valid inference for estimators that combine machine-generated measurements for the full corpus with human annotations of sampled documents. Our analysis accounts for uncertainty from document sampling, limited annotations per document, and annotator reuse. Moreover, the resulting variance formula allows us to derive the optimal allocation of a limited annotation budget for weighted corpus averages. The resulting optimal rule always prioritises increasing a document's sampling probability before increasing its number of annotations above the required minimum. It assigns more resources to documents with larger absolute weights in the target, less accurate machine predictions, or more variable annotator responses. We illustrate the method with simulations calibrated to Wikipedia toxicity annotations and an empirical application based on Shapiro and Wilson (2022).</p>
</article>

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

  <p><strong>Abstract.</strong> Topic models are often used as first-stage dimension-reduction tools before regression, with estimated document-level topic shares treated as observed covariates. This plug-in workflow creates two inferential difficulties: valid inference requires a regular first-stage-to-second-stage expansion that propagates topic-estimation uncertainty, and, at fixed document length, a document’s topic mixture is not consistently recoverable from its own words even when the population topic matrix is known. Corrected spectral moment methods for LDA provide a natural starting point: when the total Dirichlet concentration parameter is known, low-order word moments can be corrected to yield operators diagonal in the latent topic basis. We extend this idea to downstream regression.</p>

  <p>Under a finite latent Dirichlet allocation model with response residuals orthogonal to the low-order token moments used for identification, response-weighted word moments admit the same correction, and the resulting supervised operator identifies the regression coefficient β directly, without estimating document-level topic shares. The main theoretical obstacle is that the spectral correction depends on the unknown total concentration α0. We show that, for k ≥ 3 topics and under a generic finite-probe condition, α0 is identifiable by commutativity: at the true value, a family of corrected word-moment operators commute, whereas away from the truth they generically do not.</p>

  <p>This yields a feasible estimator and allows uncertainty in α̂0 to be propagated into inference for β. The estimator is asymptotically linear as the number of documents grows with fixed document length, with sandwich standard errors based on document-level moment contributions. Simulations show near-nominal coverage where plug-in topic-share regressions can undercover, and an application to top economics journals illustrates contrast inference for latent topic effects.</p>
</article>

## Work in Progress

<article class="paper-card">
  <h3>Micro-foundation for Topic Models</h3>

  <p class="paper-meta">
    <strong>Status:</strong> Work in progress
  </p>
</article>
