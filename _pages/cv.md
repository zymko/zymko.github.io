---
layout: archive
title: "Yiming's Homepage"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in The Hong Kong Polytechnic University, 2028 (expected)
* M.Sc. in Techische Universität München, 2023
* B.E. in Harbin Institute of Technology, 2019


<style>
.paper-box {
  display: flex;
  align-items: flex-start;
  border: 1px solid #e5e5e5;
  border-radius: 10px;
  background: #fff;
  box-shadow: 0 4px 10px rgba(0,0,0,0.08);
  padding: 1.5em;
  margin-bottom: 2em;
  gap: 1.5em;
  flex-wrap: wrap;
  transition: all 0.3s ease; /* 悬浮动画 */
}

.paper-box:hover {
  box-shadow: 0 8px 20px rgba(0,0,0,0.18); /* 鼠标悬浮阴影更深 */
  transform: translateY(-4px); /* 微微上浮 */
}

.paper-box-image {
  flex: 0 0 360px; /* 卡片图片大一些 */
  max-width: 100%;
  position: relative;
}

.paper-box-image img {
  width: 100%;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  object-fit: cover;
}

.paper-box-text {
  flex: 1;
  min-width: 200px;
  font-size: 15px;
  line-height: 1.6;
  color: #333;
}

/* 手机端：上下布局 */
@media (max-width: 768px) {
  .paper-box {
    flex-direction: column;
    padding: 1em;
  }

  .paper-box-image {
    width: 100%;
    margin-bottom: 1em;
  }

  .paper-box-text {
    width: 100%;
  }
}

/* arxiv 标签 */
.badge {
  position: absolute;
  top: 8px;
  left: 8px;
  background: #8B0000; /* 暗红色 */
  color: #fff;
  font-size: 0.8em;
  font-weight: bold;
  padding: 3px 10px;
  border-radius: 4px;
}

</style>

Publications
======
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arxiv</div>
      <img src='../images/infiFPO.png' alt="InfiFPO" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [InfiFPO: Implicit Model Fusion via Preference Optimization in Large Language Models](https://arxiv.org/abs/2505.13878)  
  Yanggan Gu, Zhaoyi Yan, Yuanyi Wang, **Yiming Zhang**, Qi Zhou, Fei Wu, Hongxia Yang
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arxiv</div>
      <img src='../images/InfiGFusion.png' alt="InfiGFusion" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [InfiGFusion: Graph-on-Logits Distillation via Efficient Gromov-Wasserstein for Model Fusion](https://arxiv.org/abs/2505.13893)  
  Yuanyi Wang, Zhaoyi Yan, **Yiming Zhang**, Qi Zhou, Yanggan Gu, Fei Wu, Hongxia Yang
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arxiv</div>
      <img src='../images/umm.png' alt="Unconstrained Model Merging" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [Unconstrained Model Merging for Enhanced LLM Reasoning](https://arxiv.org/abs/2410.13699)  
  **Yiming Zhang**, Baoyi He, Shengyu Zhang, Yuhao Fu, Qi Zhou, Zhijie Sang, Zijin Hong,  
  Kejing Yang, Wenjun Wang, Jianbo Yuan, Guanghan Ning, Linyi Li, Chunlin Ji, Fei Wu, Hongxia Yang
  </div>
</div>

Work Experiences
======

* **Research Assistant \| Moder Merging** \| (10.2024-05.2025)

  Supervisor: Prof. Hongxia Yang, Department of Computing, The Hong Kong Polytechnic University, Hong Kong

* **Development Engineer \| Data Closed-loop** \| (08.2023-08.2024)

  R & D Department, iMotion Automotive GmbH, Germany 

* **Data Scientisit Intern \| Continuous Intraday Market Forecasting and Optimizing** \| (05.2022-06.2023)

  Supervisor: Prof. David Wozabal, Dr. Wolfgang Ridlinger, Data Science Department, Entrix, Germany
  
Awards
======
* Graduate with merit at TUM, Germany, 07.2023
* First Prize: National College Students Mathematical Competition, 10.2016
* First Prize (Ranking No. 17): National High School Mathematical Competition, 10.2014



