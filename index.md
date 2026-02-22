---
layout: page
title: Research
filename: index.md
---

<style>
  .container {
    display: flex; /* Use flexbox for layout */
  }

  .text {
    flex: 1; /* Allow the text to grow and take up space */
    padding-right: 10px;
  }

  .image-container {
    flex: 1; /* Allow the image container to grow and take up space */
    display: flex; /* Nested flex container to center the image vertically */
    justify-content: flex-end; /* Push the image to the right */
    align-items: center; /* Center the image vertically */
    border-radius: 50%; /* Makes the container and image circular */
    border: 2px solid #000; /* Add a border to create the circle effect */
    overflow: hidden; /* Hide any content outside the circle */
  }

  .image-container img {
    max-width: 100%; /* Ensure the image doesn't exceed its container */
    max-height: 100%; /* Ensure the image doesn't exceed its container */
  }
</style>

<div class="container">
    <div class="text">
<p>Hi, I'm Alex Havrilla! I'm a research scientist at Google DeepMind studying the theoretical/practical limits of AI creativity and discovery. This work often spans a broad set of fields including Network Statistical and Approximation theory, RL, LLMs, Synthetic Data, and open-endedness.</p>
        
        
<p>I recently obtained my PhD in Machine Learning from Georgia Tech with a disseretation titled "Toward a Theory and Practice of Open-ended Reasoning with Generative Models". I was advised by (the amazing) <a href="https://wliao60.math.gatech.edu/">Wenjing Liao</a>. Also during this time I was fortunate to intern with FAIR, Microsoft Research, and Google Research. Additionally, I co-founded CarperAI: an early open-source research group studying RLHF at scale.</p>

<p>Previously, I graduated from Carnegie Mellon University with a joint MS/BS in mathematics and an additional major in computer science. My <a href="artifacts/thesis_draft_3.pdf">master's thesis</a> surveyed and proved novel Khintchine type inequalities for random variables.</p>
</div>

<div class="image-container">
    <img src="artifacts/alexh.jpg" alt="Picture">
</div>

</div>

# Research

My research covers a broad range of topics intersecting with generative modeling including LLMs, Reinforcement Learning, Diffusion Models, and statistical/approxmation theory for generative models. Recently, I've been deeply engaged in exploring ways to enhance the reasoning capabilities of Language Models (LLMs) for knowledge discovery, utilizing techniques from reinforcement learning. On the theoretical front, I focus on approximation and statistical theories for generative models, with a strong emphasis on validating these theories through empirical observations.

# Selected papers

A. Havrilla, E. Hughes, M. Samvelyan, J. Abernethy, *SPARQ: Synthetic Problem Generation for Reasoning via Quality-Diversity Algorithms*. ArXiv. <a href="https://arxiv.org/abs/2506.06499">[pdf]</a>

A. Havrilla, A. Dai, L. O'Mahony, K. Oostermeijer, V. Zisler, A. Albalak, F. Milo, S. Raparthy, K. Gandhi, B. Abbasi, D. Phung, M. Iyer, D. Mahan, C. Blagden, S. Gureja, M. Hamdy, W. Li, G. Paolini, P. Ammanamanchi, E. Meyerson, *Surveying the Effects of Quality, Diversity, and Complexity in Synthetic Data From Large Language Models*. ArXiv. <a href="https://arxiv.org/abs/2412.02980">[pdf]</a>


A. Havrilla, S. Raparthy, C. Nalmpantis, J. Yu, M. Zhuravinskyi, E. Hambro, R. Railneau, *GLoRe: When, Where, and How to Improve LLM Reasoning via Global and Local Refinements*. Accepted to ICML 2024. <a href="https://arxiv.org/abs/2402.10963">[pdf]</a>

A. Havrilla, W. Liao, *Predicting Scaling Laws with Statistical and approximation Theory for Transformer Neural Networks*. Accepted to Neurips 2024. <a href="https://arxiv.org/abs/2411.06646">[pdf]</a>

A. Havrilla, Y Du, S. Raparthy, C. Nalmpantis, J. Yu, M. Zhuravinskyi, E. Hambro, R. Railneau, *Teaching Large Language Models to Reason with Reinforcement Learning*. Submitted to Neurips 2024. <a href="https://arxiv.org/abs/2403.04642">[pdf]</a>

Y. Du, A. Havrilla, R. Railneau, *A study in RL for LLM reasoning*. Accepted to Neurips 2023 ICBINB workshop. <a href="https://openreview.net/forum?id=tCZFmDyPFm">[pdf]</a>

T. Sawada, D. Paleka, A. Havrilla, P. Vidas, A. Kranias, P. Tadepilli, A. Komatsuzaki, ARB: An Advanced Reasoning Benchmark for Large Language Modeling. To appear in Neurips 2023 MathAI workshop. <a href="https://arxiv.org/abs/2307.13692">[pdf]</a>

A. Havrilla, M. Zhuravynski, A. Tiwari, J. Tow, E. Kim, Q. Anthony, S. Biderman, L. Castricato. trlX: A Framework for Large Scale Reinforcement Learning from Human Feedback. To appear in EMNLP 2023. <a href="https://openreview.net/forum?id=TxEV8D0z0r&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DEMNLP%2F2023%2FConference%2FAuthors%23your-submissions)"> [pdf] </a>

A. Havrilla, M. Iyer, Training Large Language Models with Noisy Algorithmic Chain of Thought. To appear in ICML 2023 worksohp on Symbolic and Data driven methods for reasoning in NLP.  <a href="https://arxiv.org/abs/2402.04004">[pdf]</a>

B. Dahal, A. Havrilla, M. Chen, T. Zhao, W. Liao, On Deep Generative models for Approximation and Estimation of Distributions on Manifolds. To appear in Neurips 2022. <a href="https://arxiv.org/abs/2302.13183">[pdf]</a>

My Thesis on Sharp Khintchine type Inequalities and some New Results <a href="artifacts/thesis_draft_3.pdf">[pdf]</a>