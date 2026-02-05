---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# 👋 Hi there!

<span class='anchor' id='about-me'></span>

I'm a joint PhD student at the [Computer Graphics Lab](https://cgl.ethz.ch) of ETH Zürich and [DisneyResearch\|Studios](https://studios.disneyresearch.com/), supervised by [Prof. Dr. Markus Gross](https://cgl.ethz.ch/people/grossm/) and [Dr. Vinicius Azevedo](https://studios.disneyresearch.com/people/vinicius-da-costa-de-azevedo/). I earned my Master's degree of Computer Science in 2022 from ETH Zürich. Before that, I completed my engineering degree at Ecole polytechnique in Paris, France (equivalent to BSc & MSc). My research interests include machine learning, generative AI, and their intersection with computer graphics and artistic control.

<br>
# 🔥 News
- *2025.12*: &nbsp;🎉 [*Strands Neural Style Transfer*](https://dl.acm.org/doi/abs/10.1145/3763365) has been published at SIGGRAPH Asia 2025! 
- *2025.08*: &nbsp;🎖 *LookingGlass* has received the DCAJ Award and the Laval Virtual Award at SIGGRAPH 2025 Emerging Technologies! 
- *2025.04*: &nbsp;🎉 [*LookingGlass*](https://arxiv.org/abs/2504.08902) has been accepted to CVPR 2025 (Oral)! 
- *2025.04*: &nbsp;🎉 *How I Warped Your Noise* is now available on [ArXiv](https://arxiv.org/abs/2504.03072)! 
- *2024.05*: &nbsp;🎉 [*How I Warped Your Noise*](https://warpyournoise.github.io/) was presented at ICLR 2024 in Vienna, Austria! 

<br>
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2025 (Journal)</div>
<img src='images/papers/2025_snst.jpg'
  alt="sym"
  width="100%"
  onmouseover="this.src='images/papers/2025_snst.gif'"
  onmouseout="this.src='images/papers/2025_snst.jpg'"></div></div>
<div class='paper-box-text' markdown="1">

[**Shaping Strands with Neural Style Transfer** (SIGGRAPH Asia 2025 (Journal))](https://dl.acm.org/doi/abs/10.1145/3763365)

Beyzanur Coban, **Pascal Chang**, Guilherme G. Haetinger, Jingwei Tang, Vinicius C. Azevedo

[Paper](https://dl.acm.org/doi/abs/10.1145/3763365) / [Video](https://www.youtube.com/watch?v=dJzP2_q_7QY)

<br>

*We propose the first neural style transfer method for hair and fur strands stylization.*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025 (Oral)</div>
<img src='images/papers/2025_lookingglass.jpg'
  alt="sym"
  width="100%"
  onmouseover="this.src='images/papers/2025_lookingglass.gif'"
  onmouseout="this.src='images/papers/2025_lookingglass.jpg'"></div></div>
<div class='paper-box-text' markdown="1">

[**LookingGlass: Generative Anamorphoses via Laplacian Pyramid Warping** (CVPR 2025 Oral)](https://arxiv.org/pdf/2504.08902)

**Pascal Chang**, Sergio Sancho, Jingwei Tang, Markus Gross, Vinicius C. Azevedo

[ArXiv](https://arxiv.org/abs/2504.08902) / [Webpage](https://lookingglass-lpw.github.io/) / [Video](https://www.youtube.com/watch?v=B3AZay43688)

<br>

*We repurpose latent diffusion models to generate high-quality, complex, multi-view optical illusions such as anamorphoses.*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024 (Oral)</div>
<img src='images/papers/2024_warpyournoise.jpg'
  alt="sym"
  width="100%"
  onmouseover="this.src='images/papers/2024_warpyournoise.gif'"
  onmouseout="this.src='images/papers/2024_warpyournoise.jpg'"></div></div>
<div class='paper-box-text' markdown="1">

[**How I Warped Your Noise: a Temporally-Correlated Noise Prior for Diffusion Models** (ICLR 2024 Oral)](https://openreview.net/pdf?id=pzElnMrgSD)

**Pascal Chang**, Jingwei Tang, Markus Gross, Vinicius C. Azevedo

[ArXiv](https://arxiv.org/abs/2504.03072) / [Webpage](https://warpyournoise.github.io/) / [OpenReview](https://openreview.net/forum?id=pzElnMrgSD) / [Video](https://www.youtube.com/watch?v=LCFBq3YlwDk&t)

<br>

*We propose a method to warp a Gaussian noise sample while keeping it Gaussian and apply it to diffusion models to help temporal coherency.*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UIST 2021</div><img src='images/papers/2021_urbanbrush.jpg'
  alt="sym"
  width="100%"
  onmouseover="this.src='images/papers/2021_urbanbrush.gif'"
  onmouseout="this.src='images/papers/2021_urbanbrush.jpg'"></div></div>
<div class='paper-box-text' markdown="1">

[**Urban Brush: Intuitive and Controllable Urban Layout Editing** (UIST 2021)](https://dl.acm.org/doi/pdf/10.1145/3472749.3474787)

Xiaochen Zhou\*, **Pascal Chang**\*, Marie-Paule Cani, Bedrich Benes

[Paper](https://dl.acm.org/doi/10.1145/3472749.3474787) / [Webpage](https://urbanbrush.wordpress.com/) / [Video (short)](https://youtu.be/yFMD1NYEa2o?si=hLEbC1n9iQYp_OPG) / [Video (full)](https://youtu.be/Vzcq73o2jh4?si=kyFZRbufujF59XYI)

<br>

*We design intuitive brushes for controllable editing and authoring of procedural urban landscapes.* 

</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<br>
# 📖 Education
- *2023.01 - Present*, Joint PhD at ETH / Disney Research supervised by Prof. Dr. Markus Gross and Dr. Vinicius C. Azevedo. 
- *2020.09 - 2022.11*, MSc ETH in Computer Science (Zürich, Switzerland). 
- *2017.09 - 2022.03*, Engineering Degree from Ecole polytechnique (Paris, France).

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<br>
# 💻 Services

## Conference Reviewer

- Computer Vision and Pattern Recognition (CVPR)
- International Conference on Learning Representations (ICLR)
- European Association for Computer Graphics (Eurographics) 
- ACM SIGGRAPH

## Teaching

- [252-0543-01L  Computer Graphics](https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?semkez=2024W&ansicht=LERNMATERIALIEN&lerneinheitId=182005&lang=en)
- [252-0833-00L  Informatik II (D-MAVT)](https://vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=187116&semkez=2025S&ansicht=LEHRVERANSTALTUNGEN&lang=de)