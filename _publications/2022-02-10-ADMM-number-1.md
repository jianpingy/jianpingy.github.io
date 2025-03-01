---
title: "Adaptive uncertainty-weighted ADMM for distributed optimization"
collection: publications
category: manuscripts
permalink: /publication/2022-02-10-ADMM-number-1
excerpt: 'An ADMM-based efficient distributed optimization algorithm with guidance from uncertainty quantifications.'
date: 2022-02-10
venue: 'Journal of Applied and Numerical Optimization'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2109.01089'
citation: 'Jianping Ye, Caleb Wan, Samy Wu Fung'
---

We present AUQ-ADMM, an adaptive uncertainty-weighted consensus ADMM method for solving large-scale convex optimization problems in a distributed manner. Our key contribution is a novel adaptive weighting scheme that empirically increases the progress made by consensus ADMM scheme and is attractive when using a large number of subproblems. The weights are related to the uncertainty associated with the solutions of each subproblem, and are efficiently computed using low-rank approximations. We show AUQ-ADMM provably converges and demonstrate its effectiveness on a series of machine learning applications, including elastic net regression, multinomial logistic regression, and support vector machines. We provide an implementation based on the PyTorch package.