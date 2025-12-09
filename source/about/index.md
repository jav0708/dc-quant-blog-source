---
title: 个人简历
date: 2025-12-09 18:42:42
type: "about"
layout: page
comments: false
---

<div class="about-header" style="text-align: center; margin-bottom: 40px;">
  <img src="/img/hexo头像.jpg" alt="Avatar" style="width: 120px; height: 120px; border-radius: 50%; box-shadow: 0 0 20px rgba(0,0,0,0.1); margin-bottom: 15px;">
  <h1 style="margin: 10px 0;">陈相龙</h1>
  <p style="color: #666; font-size: 1.1em;">量化研究员 / 应用统计硕士在读</p>
  <div class="social-links" style="margin-top: 15px;">
    <a href="https://github.com/jav0708" target="_blank" style="margin: 0 10px; color: #333; text-decoration: none;"><i class="fab fa-github fa-lg"></i> Github</a>
    <a href="mailto:your-email@example.com" style="margin: 0 10px; color: #333; text-decoration: none;"><i class="fas fa-envelope fa-lg"></i> Email</a>
  </div>
</div>

> <i class="fas fa-quote-left"></i> 深度自学能力强，有钻研精神；擅长 Python 与 AI 辅助编程，致力于探索量化交易的无限可能。 <i class="fas fa-quote-right"></i>

<hr style="border: 0; height: 1px; background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0)); margin: 40px 0;">

## <i class="fas fa-graduation-cap"></i> 教育经历

<div class="timeline">
  <div class="timeline-item" style="margin-bottom: 20px; border-left: 4px solid #49b1f5; padding-left: 20px;">
    <div class="timeline-date" style="font-weight: bold; color: #49b1f5;">2025.09 - 2027.07 (预计)</div>
    <div class="timeline-title" style="font-size: 1.2em; font-weight: bold;">北京工业大学 | 应用统计 | 硕士</div>
    <div class="timeline-desc" style="color: #666;">
      <ul>
        <li>保研录取</li>
        <li>主修课程：大数据分析统计基础 (93分)</li>
        <li>荣获校级一等学习优秀奖学金</li>
      </ul>
    </div>
  </div>
  <div class="timeline-item" style="margin-bottom: 20px; border-left: 4px solid #99a9bf; padding-left: 20px;">
    <div class="timeline-date" style="font-weight: bold; color: #99a9bf;">2021.09 - 2025.07</div>
    <div class="timeline-title" style="font-size: 1.2em; font-weight: bold;">本科</div>
    <div class="timeline-desc" style="color: #666;">
      <ul>
        <li>全国大学生数学竞赛数学B类全国一等奖（北京市前五）</li>
        <li>全国大学生数学建模竞赛北京市一等奖</li>
        <li>美国大学生数学建模竞赛 H 奖</li>
        <li>校级一等科研创新奖学金</li>
      </ul>
    </div>
  </div>
</div>

## <i class="fas fa-briefcase"></i> 实习与项目经历

<div class="timeline">
  
  <!-- 量化研究员 -->
  <div class="timeline-item" style="margin-bottom: 25px;">
    <h3 style="margin-bottom: 5px;">🧬 量化研究员：遗传规划因子挖掘</h3>
    <span style="background-color: #f0f0f0; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #666;">2025.01 - 2025.03</span>
    <div style="margin-top: 10px;">
      <p><strong>职责：</strong>研究并复现遗传规划算法，挖掘过拟合程度低的日频因子。</p>
      <ul>
        <li><strong>算法构建：</strong>构建遗传规划算法，实现因子二叉树自动生成、评估与进化。</li>
        <li><strong>成果改进：</strong>实现了初始特征构建的可定制化；引入 <code>Sharpe</code> 作为适应度函数；实现 <strong>GPU 加速</strong>因子计算。</li>
        <li><strong>思考：</strong>正在探索程序化因子构建与 Ensemble 构建视角，以提高模型可解释性。</li>
      </ul>
    </div>
  </div>

  <!-- 量化策略开发与实盘 -->
  <div class="timeline-item" style="margin-bottom: 25px;">
    <h3 style="margin-bottom: 5px;">📈 量化策略开发与实盘</h3>
    <span style="background-color: #f0f0f0; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #666;">2025.10 - 至今</span>
    <div style="margin-top: 10px;">
      <p><strong>概述：</strong>系统学习因子构建与回测框架，构建个人策略并进行实盘。</p>
      <ul>
        <li><strong>策略核心：</strong>复现并改进"R方因子"（收盘价对递增常数列的线性回归R方）。</li>
        <li><strong>策略逻辑：</strong>市值与因子值双重排序（小市值+低R方），取Top 5周频调仓。</li>
        <li><strong>回测表现：</strong>2020年至今净值增长 <strong>9倍+</strong>，Sharpe Ratio <strong>~2.2</strong>。</li>
        <li><strong>实盘业绩：</strong>2025年10月启动实盘，收益率约 <strong>8%</strong>（不考虑滑点）。</li>
      </ul>
    </div>
  </div>

  <!-- BARRA模型学习 -->
  <div class="timeline-item" style="margin-bottom: 25px;">
    <h3 style="margin-bottom: 5px;">📘 BARRA 风险模型研究</h3>
    <span style="background-color: #f0f0f0; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #666;">2025.12 - 至今</span>
    <div style="margin-top: 10px;">
      <p>利用 AI 辅助学习 BARRA 风险模型体系，涵盖风格因子、因子暴露、风险分析及绩效归因。</p>
    </div>
  </div>

</div>

## <i class="fas fa-tools"></i> 技能栈

<div class="skills-container" style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown">
  <img src="https://img.shields.io/badge/Cursor_AI-000000?style=for-the-badge&logo=openai&logoColor=white" alt="AI Tools">
</div>

*   **核心能力**: 遗传算法、因子挖掘、回测系统构建
*   **工具流**: 熟练使用 Cursor 等 AI 工具辅助编程，具备对 AI 生成代码的深度掌控与优化能力。

## <i class="fas fa-trophy"></i> 荣誉奖项

| 时间 | 奖项 | 等级 |
| :--- | :--- | :--- |
| **本科** | 全国大学生数学竞赛 (数学B类) | **全国一等奖 (北京市前五)** |
| **本科** | 美国大学生数学建模竞赛 (MCM/ICM) | **H 奖 (Honorable Mention)** |
| **本科** | 全国大学生数学建模竞赛 | **北京市一等奖** |
| **高中** | 全国高中数学联赛 | **北京市二等奖** |
