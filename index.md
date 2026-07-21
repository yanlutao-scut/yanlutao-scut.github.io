---
layout: page
title: Lutao Yan
description: Lutao Yan's academic homepage, publications, research, experience, awards, and skills.
---

<div id="about" class="section-anchor"></div>

# About Me

<div class="hero-intro" markdown="1">
Hello! I am **Lutao Yan (Neal, 晏璐涛)**, an MPhil student in **Data Science and Analysis** at the [Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/). I received my BEng in Data Science and Big Data Technology from [South China University of Technology](https://www.scut.edu.cn/).

My research focuses on **multimodal learning, chart understanding, visual analytics, information retrieval, and LLM applications**. I am particularly interested in building reliable models and data systems that help people search, understand, and reason over real-world charts.
</div>

<div class="quick-links">
  <a class="site-button" href="#publications">Publications</a>
  <a class="site-button" href="#experience">Experience</a>
  <a class="site-button" href="{{ site.url }}/file/ylt_resume.pdf">CV / Resume</a>
  <a class="site-button site-button-secondary" href="mailto:lutaoyan@foxmail.com">Email</a>
</div>

## Education

<div class="timeline">
  <div class="timeline-item education-item">
    <div class="timeline-date">2025 - 2027</div>
    <div class="education-copy"><strong>Hong Kong University of Science and Technology (Guangzhou)</strong><br>MPhil, Data Science and Analysis</div>
    <div class="education-logo"><img src="{{ site.url }}/images/hkust.png" alt="HKUST(GZ) crest" loading="lazy"></div>
  </div>
  <div class="timeline-item education-item">
    <div class="timeline-date">2021 - 2025</div>
    <div class="education-copy"><strong>South China University of Technology</strong><br>BEng, Data Science and Big Data Technology, School of Future Technology</div>
    <div class="education-logo"><img src="{{ site.url }}/images/hg.png" alt="South China University of Technology crest" loading="lazy"></div>
  </div>
</div>

<h2 id="publications">Publications &amp; Research</h2>

<p class="page-intro">These selected publications form a connected research path in multimodal chart understanding—from evaluating low-level reasoning and constructing reusable training data to semantic retrieval and robust visual alignment. An asterisk (*) denotes equal contribution.</p>

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
  <aside class="publication-stage" aria-label="Research stage: Evaluate">
    <span>01</span><strong>Evaluate</strong>
    <p>Benchmark whether MLLMs can accurately read low-level chart data.</p>
  </aside>
</div>

<div class="publication-card">
  <div class="publication-main">
    <div class="publication-image"><img src="{{ site.url }}/images/Pub/kdd2025.png" alt="Overview of the ChartCards metadata generation framework" loading="lazy"></div>
    <div class="publication-content">
      <div class="publication-meta"><span>Under Review</span></div>
      <h2>ChartCards: A Chart-Metadata Generation Framework for Multi-Task Chart Understanding</h2>
      <p class="publication-authors"><strong>Lutao Yan</strong>, et al., Yuyu Luo</p>
      <p>Builds an automated chart-metadata generation framework and the 85K-chart MetaChart dataset, enabling shared training data across retrieval, question answering, and other chart tasks.</p>
      <p class="paper-links"><a href="https://arxiv.org/abs/2505.15046">Paper</a></p>
    </div>
  </div>
  <aside class="publication-stage" aria-label="Research stage: Construct">
    <span>02</span><strong>Construct</strong>
    <p>Generate reusable chart metadata and large-scale training data.</p>
  </aside>
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
  <aside class="publication-stage" aria-label="Research stage: Retrieval">
    <span>03</span><strong>Retrieval</strong>
    <p>Connect natural-language intent with real-world BI charts.</p>
  </aside>
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
  <aside class="publication-stage" aria-label="Research stage: Align">
    <span>04</span><strong>Align</strong>
    <p>Improve robust reasoning across visually diverse charts.</p>
  </aside>
</div>

{% comment %}News and Updates is intentionally hidden for now.{% endcomment %}

## Experience

### Industry Experience

<div class="experience-grid">
  <div class="experience-card">
    <div class="experience-logo brand-logo brand-jiukun" aria-label="Jiukun Investment"><strong>九坤</strong><span>JIUKUN</span></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>Jiukun Investment · Data Analysis Intern</strong><span>Jun 2026 - Oct 2026</span></div>
      <p>Supported the commercialization of AIGC products through data analysis and risk-control infrastructure, including detection of abusive content and anomalous behavior.</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo brand-logo brand-tencent" aria-label="Tencent"><strong>腾讯</strong><span>TENCENT</span></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>Tencent · WeChat Search Algorithm Intern</strong><span>Aug 2025 - Jun 2026</span></div>
      <p>Built data and sampling pipelines for mixed-ranking CTR models using real search logs, user profiles, behavioral history, and query intent. Improved personalized ranking for feed-like search scenarios through data-flow and model-flow optimization.</p>
    </div>
  </div>
</div>

### Research Experience

<div class="experience-grid">
  <div class="experience-card">
    <div class="experience-logo"><img src="{{ site.url }}/images/hkust.png" alt="HKUST(GZ) logo" loading="lazy"></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>HKUST(GZ) · Research Intern</strong><span>Jan 2024 - Present</span></div>
      <p>Advised by <a href="https://luoyuyu.vip/">Prof. Yuyu Luo</a> and Prof. Weikai Yang. Conducted four visual-analytics studies on multimodal chart understanding, data construction, and retrieval.</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo brand-logo brand-fineredline" aria-label="FineRedLine Technology"><strong>细红线</strong><span>FineRedLine</span></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>FineRedLine Technology · Algorithm Intern</strong><span>Jun 2024 - Dec 2024</span></div>
      <p>Designed LLM evaluation systems and benchmarks, and reviewed generated text and annotations against quality standards.</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo"><img src="{{ site.url }}/images/cuhk.png" alt="CUHK-Shenzhen logo" loading="lazy"></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>CUHK-Shenzhen · Research Intern</strong><span>Jul 2024 - Aug 2024</span></div>
      <p>Advised by Prof. Fangxin Wang. Explored sparse models, including mixture-of-experts architectures, for federated learning and edge intelligence.</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo"><img src="{{ site.url }}/images/hg.png" alt="South China University of Technology logo" loading="lazy"></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>South China University of Technology · Research Assistant</strong><span>Apr 2023 - May 2024</span></div>
      <p>Advised by Prof. Ye Liu and Prof. Jin Xu. Studied cross-domain lie detection and model generalization across data domains.</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo"><img src="{{ site.url }}/images/nus.png" alt="National University of Singapore logo" loading="lazy"></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>National University of Singapore · Visiting Student</strong><span>Jul 2023</span></div>
      <p>Advised by Prabhu Natarajan. Implemented traffic-sign recognition and image-enhancement methods for complex visual environments.</p>
    </div>
  </div>
</div>

## Awards

<div class="awards-list">
  <div class="award-item"><span class="award-year">2026</span><div><strong>HKUST(GZ) Red Bird MPhil Scholarship</strong><p>CNY 10,000 per month</p></div></div>
  <div class="award-item"><span class="award-year">2025</span><div><strong>HKUST(GZ) Red Bird MPhil Scholarship</strong><p>CNY 10,000 per month</p></div></div>
  <div class="award-item"><span class="award-year">2025</span><div><strong>Future Technology Taihu Science and Innovation Award</strong><p>CNY 5,000 scholarship</p></div></div>
  <div class="award-item"><span class="award-year">2024</span><div><strong>Future Technology Taihu Innovation Award</strong><p>CNY 5,000 scholarship</p></div></div>
  <div class="award-item"><span class="award-year">2023</span><div><strong>Future Technology Taihu Study Tour Award</strong><p>CNY 5,000 scholarship</p></div></div>
  <div class="award-item"><span class="award-year">2022</span><div><strong>China Undergraduate Mathematical Contest in Modeling</strong><p>Third Prize</p></div></div>
  <div class="award-item"><span class="award-year">2022</span><div><strong>Mathematical Contest in Modeling</strong><p>Successful Participant</p></div></div>
  <div class="award-item"><span class="award-year">2022</span><div><strong>Thrice-Good Student of the Year</strong><p>Top 10%</p></div></div>
  <div class="award-item"><span class="award-year">2021</span><div><strong>Baidu “PaddlePaddle” Cup</strong><p>Excellence Award</p></div></div>
</div>

## Skills

<div class="skills-grid">
  <div><strong>Programming &amp; Data</strong><p>Python, SQL, Java, C/C++, Pandas, NumPy, MySQL, Tableau</p></div>
  <div><strong>LLM &amp; Agents</strong><p>PyTorch, Transformers, RAG, agentic workflows, function calling, MCP, prompt engineering</p></div>
  <div><strong>Engineering</strong><p>OpenAI Codex, Claude Code, Git/GitHub, Linux, VS Code, Google Cloud Platform, LaTeX</p></div>
</div>
