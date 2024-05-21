---
layout: post
title:  "Gone but Not Forgotten: Improved Benchmarks for Machine Unlearning"
date:   2024-03-20 15:56:18 -0500
ad_image_path: /assets/post_assets/2024-03-20-gone-but-not-forgotten/machine_unlearning_process_square.png
ad_title: machine unlearning
ad_description: Takeaways from a literature review on Machine Unlearning.
---

It all started September 2023 with the launch of the 2023 NeurIPS Machine Unlearning Competition and a dream to compete as a part of my day job. It all ended shortly after with a long-winded 'no' from legal.

It all started back up again with support to continue looking into Machine Unlearning, with the hope that it could become a fruitful research direction for our division. 

In our preparation for the competition, we (me, Collin Abidi, and Cole Frank, supervised by Shannon Gallagher), had been analyzing the competition's evaluations and the unlearning literature, and come to the conclusion that Machine Unlearning evaluations needed work. Long story short, we published an Extended Abstract at the 7th Deep Learning Security and Privacy Workshop, co-located with the 45th IEEE Symposium on Security and Privacy. You can read it [here](https://dlsp2024.ieee-security.org/papers/dls2024-final3.pdf).

Based on demonstrated but uncommon evaluations, we recommended the use of:
- Stronger adversarial attacks and worst-case metrics for assessing threats for sophisticated attackers
- Update-leak attacks for analyzing a crucial threat model
- Iterative unlearning evaluations for studying how performance changes over time

We began implementing a suite of tools to help promote and standardize these evaluations (but were cut short due to funding constraints).