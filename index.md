---
layout: page
title: About
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
        <p>Hi, I'm Alex Havrilla, a PhD student at Georgia Tech studying generative modeling in both theory and practice. My research aims to leverage insights from both disciplines to advance each other, ultimately unifying them under a single conceptual framework. 
I have interned at <a href="https://ai.meta.com/">FAIR</a>, <a href="https://www.microsoft.com/en-us/research/blog/">Microsoft</a>, and am a cofounder of the open-source RLHF research group <a href="https://carper.ai/">CarperAI</a>.</p>

<p>I graduated from Carnegie Mellon University with a joint MS/BS in mathematics and an additional major in computer science.</p>
    </div>
    <div class="image-container">
        <img src="artifacts/alexh.jpg" alt="Picture">
    </div>
</div>

# Research

My research covers a broad range of topics intersecting with generative modeling including LLMs, Reinforcement Learning, Diffusion Models, and statistical/approxmation theory for generative models. Recently, I've been deeply engaged in exploring ways to enhance the reasoning capabilities of Language Models (LLMs) for knowledge discovery, utilizing techniques from reinforcement learning. On the theoretical front, I focus on approximation and statistical theories for generative models, with a strong emphasis on validating these theories through empirical observations.

# Papers

A. Havrilla, S. C. Raparthy, C. Nalmpantis, J. Dwivedi-Yu, M. Zhuravinskyi, E. Hambro, R. Raileanu, GLoRe: When, Where, and How to Improve LLM Reasoning via Global and Local Refinements. To appear in ICML 2024. <a href="https://arxiv.org/abs/2402.10963">[pdf]</a>

A. Havrilla, Y. Du, S. C. Raparthy, C. Nalmpantis, J. Dwivedi-Yu, M. Zhuravinskyi, E. Hambro, S. Sukhbaatar, R. Raileanu, Teaching Large Language Models to Reason with Reinforcement Learning. To appear on ArXiv. <a href="https://arxiv.org/abs/2403.04642">[pdf]</a>

T. Sawada, D. Paleka, A. Havrilla, P. Vidas, A. Kranias, P. Tadepilli, A. Komatsuzaki, ARB: An Advanced Reasoning Benchmark for Large Language Modeling. To appear in Neurips 2023 MathAI workshop. <a href="https://arxiv.org/abs/2307.13692">[pdf]</a>

H. Liu, A. Havrilla, R. Lai, W. Liao. Deep Nonparmaetric Estimation of Intrinsic Data Structures by Chart Autoencoders: Generalization Error and Robustness. To appear in Journal of Applied and Computation Harmonic Analysis. <a href="https://arxiv.org/abs/2303.09863">[pdf]</a> 

A. Havrilla, M. Zhuravynski, A. Tiwari, J. Tow, E. Kim, Q. Anthony, S. Biderman, L. Castricato. trlX: A Framework for Large Scale Reinforcement Learning from Human Feedback. To appear in EMNLP 2023. <a href="https://openreview.net/forum?id=TxEV8D0z0r&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DEMNLP%2F2023%2FConference%2FAuthors%23your-submissions)"> [pdf] </a>

A. Havrilla, K. Rojas, W. Liao, M. Tao, Dual-FNO UNet: Scale-Robust Diffusion Model for Zero-Shot Super-Resolution Image Generation. To appear in Neurips 2023 workshop on diffusion models. <a href="https://arxiv.org/abs/2401.06144">[pdf]</a>

A. Havrilla, M. Iyer, Training Large Language Models with Noisy Algorithmic Chain of Thought. To appear in ICML 2023 worksohp on Symbolic and Data driven methods for reasoning in NLP.  <a href="https://arxiv.org/abs/2402.04004">[pdf]</a>

S. Biderman, A. Tikiwari, L. Castricato, E. Hallahan, A. Havrilla, Q. Anthony, E. Raff, What Makes a Good Multimodal Embedding Space? Theoretical and Empirical Insights from Topology. To appear on ArXiv.

A. Havrilla, L. Castricato, M. Shabuland, I. Yang, S. Frazier, M. Riedl, Robust Preference Learning for Storytelling via Contrastive Reinforcement Learning. To appear on ArXiv. <a href="https://arxiv.org/abs/2210.07792">[pdf]</a>

B. Dahal, A. Havrilla, M. Chen, T. Zhao, W. Liao, On Deep Generative models for Approximation and Estimation of Distributions on Manifolds. To appear in Neurips 2022. <a href="https://arxiv.org/abs/2302.13183">[pdf]</a>

A. Havrilla, P. Nayar, T. Tkocz, Khinchin-type inequalities via Hadamard's factorisation. To appear in International Mathematics Research Notices. <a href="https://arxiv.org/abs/2102.09500">[pdf]</a>

A. Havrilla, T. Tkocz, Sharp Khinchin-type inequalities for symmetric discrete uniform random variables. To appear in Israel J. Math. <a href="https://arxiv.org/abs/1912.13345">[pdf]</a>

My Thesis on Sharp Khintchine type Inequalities and some New Results <a href="artifacts/thesis_draft_3.pdf">[pdf]</a>