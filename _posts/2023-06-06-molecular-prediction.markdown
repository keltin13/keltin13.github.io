---
layout: post
title:  "Molecular Prediction"
date:   2023-06-06 15:56:18 -0500
ad_image_path: /assets/post_assets/2023-06-06-molecular-prediction/benzene_square.png
ad_title: band-gap prediction
ad_description: My ML research in Materials Science.
---

At the start of 2021 I joined professor Noa Marom's group in Carnegie Mellon's Depeartment of Materials Science and Engineering. Her team was beginning a project to predict the band gap of molecules and crystals, the critical property in developing solar cells, and I was excited to apply my machine learning knowledge to a new domain.

I have led the project's exploration of deep learning models. We began our work by applying two state-of-the-art deep learning models designed for general molecular property prediction to a new dataset with a much more diverse set of molecules (more atoms, new elements, different structures, etc.). I set up a hyperparameter tuning system using bayesian optimization and wrote scripts to train the models (one PyTorch, one TensorFlow) on a large U.S. government GPU server. These experiments gave us strong baselines with which to buid off of.

Since the way these molecules are collected is a very time-intensive process, our main goal was to achieve a high predictive performance with as little data as possible. To this end we modified our best performing model so that we could perform active learning and ideally improve the data efficiency. We did this by replacing the model's final dense layer with a bayesian layer, where each weight has a distribution with some mean and variance. This gives us stochastic predictions, allowing us to estimate uncertainty and add the molecules with the greatest uncertainty to our training pool.
