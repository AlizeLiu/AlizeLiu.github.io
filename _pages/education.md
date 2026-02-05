---
title: "教育背景"
permalink: /education/
layout: single
author_profile: true
toc: true
---

<style>
.timeline-style {
  position: relative;
  padding-left: 30px;
  border-left: 2px solid #e2e2e2;
  margin-left: 10px;
}
.timeline-style dt {
  font-weight: bold;
  color: #33a6b8; 
  margin-top: 2em;
  position: relative;
}
.timeline-style dt::before {
  content: "";
  position: absolute;
  left: -37px;
  top: 6px;
  width: 12px;
  height: 12px;
  background-color: #33a6b8;
  border-radius: 50%;
  border: 2px solid #fff;
  z-index: 2;
}
.timeline-style dd {
  margin-left: 0;
  margin-bottom: 1em;
  display: block; /* 恢复块级布局以便浮动 */
  overflow: hidden; /* 清除浮动影响，防止线条错位 */
}
.school-logo {
  float: right; /* 【关键修改】校徽向右浮动 */
  width: 60px;  
  height: auto;
  margin-left: 20px;
  margin-bottom: 10px;
  /* 增加一个简单的阴影，让校徽更有立体感 */
  filter: drop-shadow(0 2px 4px rgba(0,0,0,0.1));
}
.edu-content {
  display: block;
}

@media (max-width: 600px) {
  .school-logo {
    width: 60px;
  }
}
</style>

<dl class="timeline-style">
  <dt>2025.09 - 至今</dt>
  <dd>
    <img src="/images/usst-logo.png" class="school-logo" alt="上海理工大学">
    <div class="edu-content">
      <strong>硕士研究生 | 生物医学工程</strong><br />
      <strong>上海理工大学</strong><br />
      <em>研究方向：生物医学工程、病理图像处理</em><br />
      <em>核心课程：医学统计学、医学图像处理、生物医学超声</em>
    </div>
  </dd>

  <dt>2020.09 - 2024.06</dt>
  <dd>
    <img src="/images/gench.png" class="school-logo" alt="上海建桥学院">
    <div class="edu-content">
      <strong>本科 | 计算机科学与技术</strong><br />
      <strong>上海建桥学院</strong><br />
       <em>核心课程：计算机网络原理、单片机应用系统制作实践、计算机组成原理、深度学习与计算机视觉</em><br />
      <em>绩点排名专业内前 10％</em><br />
      <em>相关技术：Golang, K8S, Docker 等云原生组件</em>
    </div>
  </dd>
</dl>