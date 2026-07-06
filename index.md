---
layout: page
title: About Me
nav_title: Home
---

I am a PhD student in the Carnegie Mellon School of Computer Science and a Machine Learning Researcher at the Software Engineering Institute's AI Division. My research aims to help create robust, secure, and scalable AI/ML systems. I am especially interested in AI security+safety and currently working on data poisoning and machine unlearning. I've been in to triathlons the past few years (I raced a half-Ironman!), and I also like playing chess, skiing, philosophy, and playing soccer, but it’s hard to pin me down to just one thing! You can find my resume [here](/assets/Keltin Grimes Resume.pdf) (last updated Jan. 2025).

## Publications

<ul class="pub-list">
  {% for item in site.data.publications %}
    {% include publication.html item=item %}
  {% endfor %}
</ul>

## Presentations


- Erasing Hazardous Knowledge from LLMs with Machine Unlearning, [Nexus Series: AI x Bio Workshop 1](https://www.ai4synbio.org/nexus-ai-bio-w1/) *(invited)*, November 13, 2025
- AI Engineering and LLMs, [SCADS](https://ncsu-las.org/scads/) *(invited)*, June 17, 2024, with Jasmine Ratchford
- Gone but Not Forgotten: Improved Benchmarks for Machine Unlearning, [IEEE S&P DLSP Workshop](https://dlsp2024.ieee-security.org/), May 23, 2024
- Statistical Validation of Fuel Savings from In-Flight Data Recordings, [DATAWorks](https://dataworks.testscience.org/), April 18, 2024
