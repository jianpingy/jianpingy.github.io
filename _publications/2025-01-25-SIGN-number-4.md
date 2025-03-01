---
title: "SIGN: A Statistically-Informed Gaze Network for Gaze Time Prediction"
collection: publications
category: workshops
permalink: /publication/2025-01-25-SIGN-number-4
excerpt: 'A statistically-informed neural network for eye gaze predictions.'
date: 2025-01-25
venue: 'Gaze Meets Computer Vision (GMCV) at WACV 2025'
paperurl: 'https://arxiv.org/abs/2501.17422'
citation: 'Jianping Ye, Michel Wedel'
---

We propose a first version of SIGN, a Statistically-Informed Gaze Network, to predict aggregate gaze times on images. We develop a foundational statistical model for which we derive a deep learning implementation involving CNNs and Visual Transformers, which enables the prediction of overall gaze times. The model enables us to derive from the aggregate gaze times the underlying gaze pattern as a probability map over all regions in the image, where each region's probability represents the likelihood of being gazed at across all possible scan-paths. We test SIGN's performance on AdGaze3500, a dataset of images of ads with aggregate gaze times, and on COCO-Search18, a dataset with individual-level fixation patterns collected during search. We demonstrate that SIGN (1) improves gaze duration prediction significantly over state-of-the-art deep learning benchmarks on both datasets, and (2) can deliver plausible gaze patterns that correspond to empirical fixation patterns in COCO-Search18. These results suggest that the first version of SIGN holds promise for gaze-time predictions and deserves further development.