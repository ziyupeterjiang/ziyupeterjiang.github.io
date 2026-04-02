---
title: "Research"
layout: single
classes: wide
permalink: /research/
author_profile: true
---

<style>
.paper-entry,
.wip-entry {
  padding: 1.05rem 0 1.2rem 0;
  border-bottom: 1px solid #e8e8e8;
}

.paper-title {
  margin-bottom: 0.25rem;
}

.paper-meta {
  margin: 0 0 0.55rem 0;
  font-size: 0.96em;
}

.paper-links {
  margin: 0 0 0.65rem 0;
}

.paper-links .btn {
  margin-right: 0.35rem;
  margin-bottom: 0.35rem;
}

.paper-abstract summary {
  display: inline-block;
  cursor: pointer;
  list-style: none;
}

.paper-abstract summary::-webkit-details-marker {
  display: none;
}

.paper-abstract .notice--info {
  margin-top: 0.75rem;
}
</style>

Below are current working papers and projects in progress. Drafts without public links are available upon request.

## Working Papers

<article class="paper-entry">
  <h3 class="paper-title">Identification and Estimation of Simultaneous Equation Models Using Higher-Order Cumulant Restrictions</h3>
  <p class="paper-meta">
    <strong>Submission status:</strong> Revise and Resubmit at <em>Journal of Econometrics</em><br>
    <strong>Public version:</strong> arXiv working paper (2025)
  </p>

  <div class="paper-links">
    <a href="https://arxiv.org/abs/2501.06777" class="btn btn--primary btn--small">arXiv</a>
    <!-- Optional examples -->
    <!-- <a href="/files/paper.pdf" class="btn btn--info btn--small">PDF</a> -->
    <!-- <a href="/files/slides.pdf" class="btn btn--light-outline btn--small">Slides</a> -->
    <!-- <a href="https://github.com/yourusername/project" class="btn btn--light-outline btn--small">Code</a> -->
  </div>

  <details class="paper-abstract">
    <summary><span class="btn btn--success btn--small">Abstract</span></summary>
    <div class="notice--info">
      <p>TIdentifying structural parameters in linear simultaneous‐equation models is a fundamental challenge in economics and related fields. Recent work leverages higher‐order moments, exploiting the fact that non‑Gaussian data contain more structural information than Gaussian data. While many of these contributions still require zero covariance among structural errors, we show that this assumption—and the associated pre‑whitening step—can be dispensed with. Specifically, we present a novel identification argument showing that, under a diagonality condition on higher‑order cumulants, the structural parameter matrix can be identified by solving a simple eigenvector problem. This insight motivates a straightforward sample‑analogue estimator that is root‑\(n\) consistent, asymptotically normal, and trivial to compute. Moreover, when uncorrelatedness is an essential model feature—as in vector autoregressive models---our framework provides a transparent misspecification test based on the same higher-order orthogonality conditions used in prior work. Monte Carlo experiments demonstrate desirable finite-sample performance, and we further illustrate the method's practical value in two empirical applications.</p>
    </div>
  </details>
</article>

<article class="paper-entry">
  <h3 class="paper-title">A complete spectral solution to the Latent Dirichlet Allocation model</h3>
  <p class="paper-meta">
    <strong>Submission status:</strong> Working paper<br>
    <strong>Version:</strong> Draft in progress
    <!-- Optional -->
    <!-- <br><strong>Coauthors:</strong> Name One, Name Two -->
  </p>

  <div class="paper-links">
    <!-- Add links once available -->
    <!-- <a href="/files/lda-paper.pdf" class="btn btn--primary btn--small">PDF</a> -->
  </div>

  <details class="paper-abstract">
    <summary><span class="btn btn--success btn--small">Abstract</span></summary>
    <div class="notice--info">
      <p>Text-as-data has become central to empirical economics, with topic models providing a convenient, low-dimensional representation of documents for downstream analysis. A persistent challenge is identification: without strong restrictions on topics or mixtures, standard topic models are not identified, and widely used Bayesian estimators can be sensitive to prior choices. We revisit Latent Dirichlet Allocation (LDA) from a frequentist perspective and develop identification and estimation results tailored to econometric applications that use estimated topic proportions as regressors.

Our first contribution is a simple identification argument for LDA when the Dirichlet concentration parameter \( \alpha_0 \) is known. Building on this, we show that when the number of topics satisfies \( K \ge 3 \), \( \alpha_0 \) itself is identified from low-order moments and therefore need not be specified \emph{a priori}. Together with our first result, this implies that for \( K \ge 3 \) the LDA model is fully identifiable from the data (up to permutation of topic labels). We further provide sufficient conditions that make identification---and practical estimation---of \( \alpha_0 \) more direct. Motivated by these results, we construct a spectral, method-of-moments estimator based on adjusted second- and third-order moments that jointly recovers the topic--word probabilities and parameters relevant for downstream regression. We establish rigorous asymptotic guarantees for the topic parameters and for regression coefficients formed from estimated topic proportions. A Monte Carlo study evaluates finite-sample performance and illustrates the practical implications for applied work. Collectively, our results deliver identification without anchor-word or strong geometric assumptions and furnish computationally tractable estimation with formal statistical guarantees for econometric use.</p>
    </div>
  </details>
</article>

## Work in Progress

<article class="wip-entry">
  <h3 class="paper-title">[Project title]</h3>
  <p class="paper-meta">
    <strong>Status:</strong> Work in progress
    <!-- Optional -->
    <!-- <br><strong>Coauthors:</strong> Name -->
  </p>
  <p>One-sentence description of the project.</p>
</article>

<article class="wip-entry">
  <h3 class="paper-title">[Project title]</h3>
  <p class="paper-meta">
    <strong>Status:</strong> Early-stage project
  </p>
  <p>One-sentence description of the project.</p>
</article>
