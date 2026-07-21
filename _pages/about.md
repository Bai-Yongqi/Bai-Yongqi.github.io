---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am an undergraduate at HKUST, double-majoring in Mathematics and Quantitative Social Analysis. I work as a research assistant in the Department of Computer Science and Engineering, advised by Prof. Song Guo and Prof. Jie Zhang.

My research interests center on reinforcement learning and world-model planning for LLM/VLM agents, multi-turn decision-making under partial observability, and applications to quantitative finance.

I will be a visiting student at the University of Virginia in Fall 2026.


# 🔥 News
- *2026.07*: &nbsp;Released a heads-up no-limit Texas Hold'em AI, playable in-browser. [[Demo]](https://bai-yongqi.github.io/texas-holdem-ai/) [[Code]](https://github.com/Bai-Yongqi/texas-holdem-ai)
- *2026.02*: &nbsp;Joined HKUST CSE as a research assistant with Prof. Song Guo and Prof. Jie Zhang.
- *2024.09*: &nbsp;Started at HKUST, double major in Mathematics and Quantitative Social Analysis.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/wmp.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**World-Model Planning for Vision-Language Agents**

*Under review*

Extends adaptive-lookahead world-model planning (Imagine-then-Plan) from text-only LLM agents to vision-language agents under a POIMDP formulation. A zero-shot ablation across 150 scenarios showed adaptive lookahead does not help off the shelf: K = 0 / 1 / adaptive gave 24% / 16% / 20%. The payoff appears only after the base policy is RL-trained; a 150-step GRPO run on Qwen2.5-VL-3B then lifted validation success from 27.3% to 37.9%.
</div>
</div>

# 🚀 Projects

**Texas Hold'em AI — Heads-Up No-Limit, CFR + Opponent Modeling** &nbsp; [[Play in browser]](https://bai-yongqi.github.io/texas-holdem-ai/) [[Code]](https://github.com/Bai-Yongqi/texas-holdem-ai)

Five difficulty levels, from a rule-based baseline to a CFR near-equilibrium solver with an opponent-modeling layer. Against the same weak opponent, the pure equilibrium agent wins +4.4 bb/100 and the exploitative one wins +36.4 — same strategy underneath, the difference is entirely the layer that notices the opponent folds too much. CFR correctness was checked on Kuhn Poker, where the equilibrium is known exactly; exploitability then fell from 57.2 to 3.7 mbb/hand. Runs entirely in-browser via Pyodide.

**Systematic Factor Investing &amp; Constrained Portfolio Optimization**

Nothing cleared the bar. That is the result. No configuration passed a Deflated Sharpe Ratio of 0.95 across an N = 38 trial registry, 28-path Combinatorial Purged Cross-Validation, and a pre-registered one-shot holdout. The verifiable ceiling on free public data is about 0.66 gross. The binding constraint is the number of independent time-series regimes available, not the factor set. Pipeline: 24 factors over the S&amp;P 500, sector and beta neutralization, Ledoit-Wolf shrinkage covariance, and a fully constrained cvxpy mean-variance optimizer.

**Fund Attribution from NAV Series**

Decomposes multi-cap quantitative funds' excess returns using only published NAV series, via BARRA-style return-based regression, separating selection alpha from size, value, and momentum style exposure.

# 💼 Experience

<div style="display:flex; align-items:center; gap:14px; margin:16px 0;">
  <img src="images/logos/hkust.png" alt="HKUST" style="width:48px; height:48px; object-fit:contain; flex-shrink:0;">
  <div><strong>Research Assistant, HKUST CSE</strong> <span style="opacity:.65;">· 2026.02 – present</span><br>Advised by Prof. Song Guo and Prof. Jie Zhang.</div>
</div>

<div style="display:flex; align-items:center; gap:14px; margin:16px 0;">
  <img src="images/logos/huatai.svg" alt="Huatai United Securities" style="width:48px; height:48px; object-fit:contain; flex-shrink:0;">
  <div><strong>Investment Banking Division Intern, Huatai United Securities</strong> <span style="opacity:.65;">· Shanghai · 2026.05 – present</span></div>
</div>

<div style="display:flex; align-items:center; gap:14px; margin:16px 0;">
  <img src="images/logos/cash.png" alt="CASH Financial Services Group" style="width:48px; height:48px; object-fit:contain; flex-shrink:0;">
  <div><strong>Securities Trading Intern, Wealth Management, CASH Financial Services Group</strong> <span style="opacity:.65;">· Hong Kong · 2026.02 – 2026.04</span></div>
</div>

<div style="display:flex; align-items:center; gap:14px; margin:16px 0;">
  <img src="images/logos/citic.svg" alt="CITIC Securities" style="width:48px; height:48px; object-fit:contain; flex-shrink:0;">
  <div><strong>Investment Advisory Intern, CITIC Securities</strong> <span style="opacity:.65;">· Xi'an · 2025.12 – 2026.02</span></div>
</div>

# 📖 Education
- *2024.09 – 2028.06*, B.Sc. Mathematics &amp; Quantitative Social Analysis, HKUST
- *2026 Fall*, Visiting student, University of Virginia
