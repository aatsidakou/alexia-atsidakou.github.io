---
layout: archive
title: "Publication List"
permalink: /publications/
author_profile: true
---



[**Bayesian Fixed-Budget Best-Arm Identification**](https://arxiv.org/abs/2211.08572)  
AA, Sumeet Katariya, Sujay Sanghavi, Branislav Kveton  
(pre-print)  

[**Contextual Pandora’s Box**](https://arxiv.org/abs/2205.13114)  
AA, Constantine Caramanis, Evangelia Gergatsouli, Orestis Papadigenopoulos, Christos Tzamos  
AAAI Conference on Artificial Intelligence (AAAI) 2024  

[**Finite-Time Logarithmic Bayes Regret Upper Bounds**](https://arxiv.org/abs/2306.09136)  
AA, Branislav Kveton, Sumeet Katariya, Constantine Caramanis, Sujay Sanghavi  
Conference on Neural Information Processing Systems (NeurIPS) 2023  

[**Asymptotically-Optimal Gaussian Bandits with Side Observations**](https://proceedings.mlr.press/v162/atsidakou22a.html)  
AA, Orestis Papadigenopoulos, Constantine Caramanis, Sujay Sanghavi, Sanjay Shakkottai  
International Conference of Machine Learning (ICML) 2022  

[**Towards Statistical and Computational Complexities of Polyak Step
Size Gradient Descent**](https://arxiv.org/abs/2110.07810)  
Tongzheng Ren, Fuheng Cui, AA, Sujay Sanghavi, Nhat Ho  
Artificial Intelligence and Statistics (AISTATS) 2022  

[**Combinatorial Blocking Bandits with Stochastic Delays**](https://arxiv.org/abs/2105.10625)  
AA, Orestis Papadigenopoulos, Soumya Basu, Constantine Caramanis, Sanjay Shakkottai  
International Conference of Machine Learning (ICML) 2021  

[**Parallel Model Exploration for Tumor Treatment Simulations**](https://arxiv.org/abs/2103.14132)  
Charilaos Akasiadis, Miguel Ponce-de-Leon, Arnau Montagud, Evangelos Michelioudakis, AA, Elias Alevizos, Alexander Artikis, Alfonso Valencia, Georgios Paliouras  
Computational Intelligence Journal 2021  




{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my publications on my Google Scholar <a href="{{site.author.googlescholar}}">profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
