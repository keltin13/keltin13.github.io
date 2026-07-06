---
layout: page
title: About Me
nav_title: Home
---

I am a Machine Learning Researcher at Carnegie Mellon University's Software Engineering Institute, working on research projects to help create robust, secure, and scalable AI/ML systems. I graduated from Carnegie Mellon University with a major in Statistics and Machine Learning, and an additional major in Computer Science. I love all things data, machine learning, and artificial intelligence. I've been in to triathlons the past few years (I raced a half-Ironman!), and I also like playing chess, skiing, philosophy, and playing soccer, but it's hard to pin me down to just one thing! You can find my resume [here](/assets/Keltin Grimes Resume.pdf).

## Publications

<ul class="pub-list">
  {% for item in site.data.publications %}
    {% include publication.html item=item %}
  {% endfor %}
</ul>

## Presentations


- AI Engineering and LLMs, [SCADS](https://ncsu-las.org/scads/) *(invited)*, June 17, 2024, with Jasmine Ratchford
- Gone but Not Forgotten: Improved Benchmarks for Machine Unlearning, [IEEE S&P DLSP Workshop](https://dlsp2024.ieee-security.org/), May 23, 2024
- Statistical Validation of Fuel Savings from In-Flight Data Recordings, [DATAWorks](https://dataworks.testscience.org/), April 18, 2024
