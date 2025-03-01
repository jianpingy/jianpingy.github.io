---
title: "Contextual Advertising with Theory-Informed Machine Learning"
collection: publications
category: preprints
permalink: /publication/2024-11-01-Contextual_Ad-number-3
excerpt: 'A novel and comprehensive predictive model for contextual advertising.'
date: 2024-11-01
venue: 'SSRN'
slidesurl: #'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5007216'
citation: 'Jianping Ye, Michel Wedel, Rik Pieters'
---

Contextual advertising involves matching features of ads to features of the media context in which they appear. We propose a theoretical framework that organizes these features and develop machine learning methods, grounded in that theoretical framework, to extract the features and to predict ad and brand attention. Our approach includes a Multimodal Large Language Model to extract high-level topics that predict the match of an ad to its context, as well as an XGBoost prediction model. Our research draws upon an eye-tracking data set containing 3531 digital display ads, along with their context, and aggregate ad and brand gaze times. We investigate the predictive performance of our approach and two feature learning methods, VGG16 and ResNet50. We find that both XGBoost and ResNet50 make highly accurate predictions. The ResNet50 model performs best in predicting attention to the ad, while our XGBoost model performs best in predicting attention to the brand. Importantly, for out-of-distribution ads we find that our theory-informed XGBoost model performs better than ResNet50. Shapley values reveal the contributions of ad and context features to the predictions. We demonstrate that the theory-informed XGBoost approach is more effective than ResNet50 in an application to contextual advertising.