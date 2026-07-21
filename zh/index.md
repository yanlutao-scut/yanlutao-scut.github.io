---
layout: page
permalink: /zh/index.html
title: 晏璐涛
description: 晏璐涛的个人学术主页，包含论文成果、研究方向、教育背景、个人经历、获奖情况与专业技能。
lang: zh
---

<div id="about" class="section-anchor"></div>

# 关于我

<div class="hero-intro" markdown="1">
你好！我是 **晏璐涛（Lutao Yan，Neal）**，现于[香港科技大学（广州）](https://www.hkust-gz.edu.cn/)攻读**数据科学与分析**哲学硕士（MPhil）。本科毕业于[华南理工大学](https://www.scut.edu.cn/)未来技术学院数据科学与大数据技术专业。

我的研究聚焦于**多模态学习、图表理解、可视分析、信息检索及大语言模型应用**，尤其关注如何构建可靠的模型与数据系统，帮助用户检索、理解并推理真实世界中的图表信息。
</div>

<div class="quick-links">
  <a class="site-button" href="#publications">论文成果</a>
  <a class="site-button" href="#experience">个人经历</a>
  <a class="site-button" href="{{ site.url }}/file/ylt_resume.pdf">个人简历</a>
  <a class="site-button site-button-secondary" href="mailto:lutaoyan@foxmail.com">邮箱</a>
</div>

<h2 id="education">教育背景</h2>

<div class="timeline">
  <div class="timeline-item education-item">
    <div class="timeline-date">2025 - 2027</div>
    <div class="education-copy"><strong>香港科技大学（广州）</strong><br>数据科学与分析，哲学硕士</div>
    <div class="education-logo"><img src="{{ site.url }}/images/hkust.png" alt="香港科技大学（广州）校徽" loading="lazy"></div>
  </div>
  <div class="timeline-item education-item">
    <div class="timeline-date">2021 - 2025</div>
    <div class="education-copy"><strong>华南理工大学</strong><br>未来技术学院，数据科学与大数据技术，工学学士</div>
    <div class="education-logo"><img src="{{ site.url }}/images/hg.png" alt="华南理工大学校徽" loading="lazy"></div>
  </div>
</div>

<h2 id="publications">论文成果与研究主线</h2>

<p class="page-intro">以下四项工作围绕多模态图表理解形成连续的研究路径：从低层推理评测与可复用训练数据构建，逐步拓展到语义检索和鲁棒视觉对齐。星号（*）表示共同贡献。</p>

<div class="publication-card">
  <div class="publication-main">
    <div class="publication-image"><img src="{{ site.url }}/images/Pub/emnlp2024.png" alt="ChartInsights 基准概览" loading="lazy"></div>
    <div class="publication-content">
      <div class="publication-meta"><span>EMNLP 2024 Findings</span><span>共同第一作者</span></div>
      <h2>ChartInsights: Evaluating Multimodal Large Language Models for Low-Level Chart Question Answering</h2>
      <p class="publication-authors">Yifan Wu*, <strong>Lutao Yan*</strong>, Leixian Shen, Yunhai Wang, Nan Tang, Yuyu Luo</p>
      <p>构建覆盖 10 类任务和 7 种图表类型的低层 ChartQA 基准，评测 19 个多模态模型，并提出 Chain-of-Charts 提示策略以提升图表数据问答能力。</p>
      <p class="paper-links"><a href="https://arxiv.org/abs/2405.07001">论文</a></p>
    </div>
  </div>
  <aside class="publication-stage" aria-label="研究阶段：评测">
    <span>01</span><strong>评测</strong>
    <p>评估多模态大模型能否准确读取图表中的低层数据。</p>
  </aside>
</div>

<div class="publication-card">
  <div class="publication-main">
    <div class="publication-image"><img src="{{ site.url }}/images/Pub/kdd2025.png" alt="ChartCards 元数据生成框架概览" loading="lazy"></div>
    <div class="publication-content">
      <div class="publication-meta"><span>审稿中</span></div>
      <h2>ChartCards: A Chart-Metadata Generation Framework for Multi-Task Chart Understanding</h2>
      <p class="publication-authors"><strong>Lutao Yan</strong>, et al., Yuyu Luo</p>
      <p>提出自动化图表元数据生成框架并构建包含 8.5 万张图表的 MetaChart 数据集，为检索、问答等多类图表任务提供可复用的统一训练数据。</p>
      <p class="paper-links"><a href="https://arxiv.org/abs/2505.15046">论文</a></p>
    </div>
  </div>
  <aside class="publication-stage" aria-label="研究阶段：构建">
    <span>02</span><strong>构建</strong>
    <p>自动生成可复用的图表元数据与大规模训练数据。</p>
  </aside>
</div>

<div class="publication-card">
  <div class="publication-main">
    <div class="publication-image"><img src="{{ site.url }}/images/Pub/sigir2025.png" alt="ChartFinder 文本到图表检索框架概览" loading="lazy"></div>
    <div class="publication-content">
      <div class="publication-meta"><span>ACL 2026</span><span>共同第一作者</span></div>
      <h2>Boosting Text-to-Chart Retrieval through Training with Synthesized Semantic Insights</h2>
      <p class="publication-authors"><strong>Lutao Yan*</strong>, et al., Yuyu Luo</p>
      <p>构建真实商业智能场景基准 CRBench，并提出分层语义洞察训练管线训练 ChartFinder，将精确文本到图表检索的 NDCG@10 提升至 66.9%。</p>
      <p class="paper-links"><a href="https://arxiv.org/abs/2505.10043">论文</a></p>
    </div>
  </div>
  <aside class="publication-stage" aria-label="研究阶段：检索">
    <span>03</span><strong>检索</strong>
    <p>连接自然语言查询意图与真实商业智能图表。</p>
  </aside>
</div>

<div class="publication-card">
  <div class="publication-main">
    <div class="publication-image"><img src="{{ site.url }}/images/Pub/chartalign.png" alt="ChartAlign 实例级视觉对齐方法概览" loading="lazy"></div>
    <div class="publication-content">
      <div class="publication-meta"><span>CVPR 2026 Findings</span></div>
      <h2>ChartAlign: Instance-Level Visual Alignment for Robust Chart Understanding in MLLMs</h2>
      <p class="publication-authors"><strong>Lutao Yan</strong>, et al., Weikai Yang</p>
      <p>构建语义等价但视觉风格多样的 ChartPairs，并在实例层面对齐图像编码器，提升多模态模型在无文字标签与艺术化图表上的鲁棒推理能力。</p>
      <p class="paper-links"><a href="{{ site.url }}/file/chartalign.pdf">论文</a></p>
    </div>
  </div>
  <aside class="publication-stage" aria-label="研究阶段：对齐">
    <span>04</span><strong>对齐</strong>
    <p>提升模型面对不同视觉风格图表时的鲁棒推理能力。</p>
  </aside>
</div>

<h2 id="experience">个人经历</h2>

### 实习经历

<div class="experience-grid">
  <div class="experience-card">
    <div class="experience-logo brand-logo brand-jiukun" aria-label="九坤投资"><strong>九坤</strong><span>JIUKUN</span></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>九坤投资 · 数据分析实习生</strong><span>2026.06 - 2026.10</span></div>
      <p>参与创新业务线 AIGC 产品商业化，负责数据分析与业务中台风控建设，识别黑灰产内容及异常行为，支持产品安全运营与商业化落地。</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo brand-logo brand-tencent" aria-label="腾讯"><strong>腾讯</strong><span>TENCENT</span></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>腾讯 · 微信搜一搜算法实习生</strong><span>2025.08 - 2026.06</span></div>
      <p>面向微信搜一搜混排 CTR 预估，基于真实搜索日志、用户画像、行为历史及查询意图构建数据与采样管线；从数据流与模型流两条路径优化可刷场景下的个性化排序与点击率预估。</p>
    </div>
  </div>
</div>

### 科研经历

<div class="experience-grid">
  <div class="experience-card">
    <div class="experience-logo"><img src="{{ site.url }}/images/hkust.png" alt="香港科技大学（广州）校徽" loading="lazy"></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>香港科技大学（广州）· 研究实习生</strong><span>2024.01 - 至今</span></div>
      <p>导师：<a href="https://luoyuyu.vip/">骆昱宇教授</a>、杨维铠教授。围绕多模态大模型的图表理解、数据构建与检索开展 4 项可视分析研究工作。</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo brand-logo brand-fineredline" aria-label="细红线科技"><strong>细红线</strong><span>FineRedLine</span></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>细红线科技 · 算法实习生</strong><span>2024.06 - 2024.12</span></div>
      <p>设计大语言模型评测系统与基准，并依据质量标准审核生成文本和数据标注结果。</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo"><img src="{{ site.url }}/images/cuhk.png" alt="香港中文大学（深圳）校徽" loading="lazy"></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>香港中文大学（深圳）· 研究实习生</strong><span>2024.07 - 2024.08</span></div>
      <p>导师：王方鑫教授。探索混合专家等稀疏模型在联邦学习与边缘智能场景中的应用。</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo"><img src="{{ site.url }}/images/hg.png" alt="华南理工大学校徽" loading="lazy"></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>华南理工大学 · 科研助理</strong><span>2023.04 - 2024.05</span></div>
      <p>导师：刘烨教授、徐进教授。研究跨领域谎言检测及模型在不同数据域之间的泛化能力。</p>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo"><img src="{{ site.url }}/images/nus.png" alt="新加坡国立大学校徽" loading="lazy"></div>
    <div class="experience-copy">
      <div class="experience-heading"><strong>新加坡国立大学 · 访问学生</strong><span>2023.07</span></div>
      <p>导师：Prabhu Natarajan。实现复杂视觉环境下的交通标志识别与图像增强方法。</p>
    </div>
  </div>
</div>

<h2 id="awards">获奖情况</h2>

<div class="awards-list">
  <div class="award-item"><span class="award-year">2026</span><div><strong>香港科技大学（广州）红鸟硕士研究生奖学金</strong><p>人民币 10,000 元/月</p></div></div>
  <div class="award-item"><span class="award-year">2025</span><div><strong>香港科技大学（广州）红鸟硕士研究生奖学金</strong><p>人民币 10,000 元/月</p></div></div>
  <div class="award-item"><span class="award-year">2025</span><div><strong>未来技术太湖科创奖</strong><p>人民币 5,000 元奖学金</p></div></div>
  <div class="award-item"><span class="award-year">2024</span><div><strong>未来技术太湖创新奖</strong><p>人民币 5,000 元奖学金</p></div></div>
  <div class="award-item"><span class="award-year">2023</span><div><strong>未来技术太湖游学奖</strong><p>人民币 5,000 元奖学金</p></div></div>
  <div class="award-item"><span class="award-year">2022</span><div><strong>全国大学生数学建模竞赛</strong><p>三等奖</p></div></div>
  <div class="award-item"><span class="award-year">2022</span><div><strong>美国大学生数学建模竞赛</strong><p>成功参赛奖</p></div></div>
  <div class="award-item"><span class="award-year">2022</span><div><strong>年度三好学生</strong><p>前 10%</p></div></div>
  <div class="award-item"><span class="award-year">2021</span><div><strong>百度“飞桨”杯</strong><p>优秀奖</p></div></div>
</div>

<h2 id="skills">专业技能</h2>

<div class="skills-grid">
  <div><strong>编程与数据</strong><p>Python、SQL、Java、C/C++、Pandas、NumPy、MySQL、Tableau</p></div>
  <div><strong>大模型与智能体</strong><p>PyTorch、Transformers、RAG、智能体工作流、函数调用、MCP、提示词工程</p></div>
  <div><strong>工程工具</strong><p>OpenAI Codex、Claude Code、Git/GitHub、Linux、VS Code、Google Cloud Platform、LaTeX</p></div>
</div>
