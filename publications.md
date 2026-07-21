---
layout: page
permalink: /publications/index.html
title: Publications
description: Publications by Lutao Yan on multimodal chart understanding and retrieval.
---

# Publications & Research

<p class="page-intro">Four connected studies spanning chart evaluation, data construction, semantic retrieval, and robust visual alignment. An asterisk (*) denotes equal contribution.</p>

<div class="publication-card">
  <div class="publication-main">
    <div class="publication-image"><img src="{{ site.url }}/images/Pub/emnlp2024.png" alt="Overview of the ChartInsights benchmark" loading="lazy"></div>
    <div class="publication-content">
      <div class="publication-meta"><span>EMNLP 2024 Findings</span><span>Co-first author</span></div>
      <h2>ChartInsights: Evaluating Multimodal Large Language Models for Low-Level Chart Question Answering</h2>
      <p class="publication-authors">Yifan Wu*, <strong>Lutao Yan*</strong>, Leixian Shen, Yunhai Wang, Nan Tang, Yuyu Luo</p>
      <p>Introduces a low-level ChartQA benchmark covering 10 tasks and 7 chart types, evaluates 19 multimodal models, and proposes Chain-of-Charts to improve chart data question answering.</p>
      <p class="paper-links"><a href="https://arxiv.org/abs/2405.07001">Paper</a></p>
    </div>
  </div>
  <aside class="publication-stage" aria-label="Research stage: Evaluate"><span>01</span><strong>Evaluate</strong><p>Benchmark whether MLLMs can accurately read low-level chart data.</p></aside>
</div>

<div class="publication-card">
  <div class="publication-main">
    <div class="publication-image"><img src="{{ site.url }}/images/Pub/kdd2025.png" alt="Overview of the ChartCards metadata generation framework" loading="lazy"></div>
    <div class="publication-content">
      <div class="publication-meta"><span>Under Review</span><span>Co-first author</span></div>
      <h2>ChartCards: A Chart-Metadata Generation Framework for Multi-Task Chart Understanding</h2>
      <p class="publication-authors"><strong>Lutao Yan*</strong>, et al., Yuyu Luo</p>
      <p>Builds an automated chart-metadata generation framework and the 85K-chart MetaChart dataset, enabling shared training data across retrieval, question answering, and other chart tasks.</p>
      <p class="paper-links"><a href="https://arxiv.org/abs/2505.15046">Paper</a></p>
    </div>
  </div>
  <aside class="publication-stage" aria-label="Research stage: Construct"><span>02</span><strong>Construct</strong><p>Generate reusable chart metadata and large-scale training data.</p></aside>
</div>

<div class="publication-card">
  <div class="publication-main">
    <div class="publication-image"><img src="{{ site.url }}/images/Pub/sigir2025.png" alt="Overview of ChartFinder for text-to-chart retrieval" loading="lazy"></div>
    <div class="publication-content">
      <div class="publication-meta"><span>ACL 2026</span><span>Co-first author</span></div>
      <h2>Boosting Text-to-Chart Retrieval through Training with Synthesized Semantic Insights</h2>
      <p class="publication-authors"><strong>Lutao Yan*</strong>, et al., Yuyu Luo</p>
      <p>Introduces the real-world BI benchmark CRBench and a hierarchical semantic-insight training pipeline for ChartFinder, improving precise text-to-chart retrieval NDCG@10 to 66.9%.</p>
      <p class="paper-links"><a href="https://arxiv.org/abs/2505.10043">Paper</a></p>
    </div>
  </div>
  <aside class="publication-stage" aria-label="Research stage: Retrieval"><span>03</span><strong>Retrieval</strong><p>Connect natural-language intent with real-world BI charts.</p></aside>
</div>

<div class="publication-card">
  <div class="publication-main">
    <div class="publication-image"><img src="{{ site.url }}/images/Pub/chartalign.png" alt="Overview of the ChartAlign instance-level visual alignment method" loading="lazy"></div>
    <div class="publication-content">
      <div class="publication-meta"><span>CVPR 2026 Findings</span></div>
      <h2>ChartAlign: Instance-Level Visual Alignment for Robust Chart Understanding in MLLMs</h2>
      <p class="publication-authors"><strong>Lutao Yan</strong>, et al., Weikai Yang</p>
      <p>Constructs visually diverse but semantically equivalent ChartPairs and aligns image encoders at the instance level, improving robust multimodal reasoning on unlabeled and artistic charts.</p>
      <p class="paper-links"><a href="{{ site.url }}/file/chartalign.pdf">Paper</a></p>
    </div>
  </div>
  <aside class="publication-stage" aria-label="Research stage: Align"><span>04</span><strong>Align</strong><p>Improve robust reasoning across visually diverse charts.</p></aside>
</div>
