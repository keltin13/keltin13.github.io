---
layout: post
title:  "Toy Models of Superposition - Code Companion"
date:   2024-05-13 20:41:18 -0500
ad_image_path: /assets/post_assets/2024-05-13-toy-models-of-superposition-code-companion/feature_dimensionality_over_time_square.png
ad_title: replicating TMS
ad_description: My code companion for Toy Models of Superposition.
---

In the fall of 2023, I came across Anthropic's paper [Toy Model of Superposition](https://transformer-circuits.pub/2022/toy_model/index.html) (TMS). It is a fascinating (and long!) exploration into the phenomenon of 'superposition' in artifical neural networks, where networks store more features than would naively be expected based on the size of the model. As I went over the paper in depth, I started recreating some of the plots from the paper. I also started exploring variations and extensions of the setups from the paper, and built up a decent number of plotting functions (I also rewrote my model training code a couple times!). 

In the spring of 2024, I decided to go the distance and replicate every plot in TMS, cleaning up what I had and implementing the rest. Matplotlib and I are best friends now! You can check out the finished notebook in a couple places:

- Colab (Interactive): [https://colab.research.google.com/drive/1v76DJEiHsFuEQu9Revu0k--zVYeS1fig?usp=sharing](https://colab.research.google.com/drive/1v76DJEiHsFuEQu9Revu0k--zVYeS1fig?usp=sharing)
- Github: [https://github.com/keltin13/toy-models-of-superposition](https://github.com/keltin13/toy-models-of-superposition)

Here's a sneak peak at some of the plots (read TMS for context!):

<img src="/assets/post_assets/2024-05-13-toy-models-of-superposition-code-companion/feature_dimensionality_over_time.png" style="width:75%; margin: 5px auto; display: block;">

<img src="/assets/post_assets/2024-05-13-toy-models-of-superposition-code-companion/dimensions_per_feature.png" style="width:75%; margin: 5px auto; display: block;">

<img src="/assets/post_assets/2024-05-13-toy-models-of-superposition-code-companion/feature_plot_3D.png" style="width:75%; margin: 5px auto; display: block;">