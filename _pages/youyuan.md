---
permalink: /
title: ""
excerpt: ""
author_profile: true
---

<span class="anchor" id="about-me"></span>

# Youyuan Tang (唐友源)

<div class="profile-lead">
  <p class="role-line lang-en"><i class="fas fa-user-graduate" aria-hidden="true"></i> Ph.D. Student in Electronic Information, Hunan University</p>
  <p class="role-line cn lang-zh"><i class="fas fa-user-graduate" aria-hidden="true"></i> 湖南大学人工智能与机器人学院电子信息博士研究生</p>
  <div class="profile-meta">
    <span class="lang-en"><i class="fas fa-university" aria-hidden="true"></i> School of Robotics and Artificial Intelligence, Hunan University</span>
    <span class="lang-zh"><i class="fas fa-university" aria-hidden="true"></i> 湖南大学人工智能与机器人学院</span>
    <span><i class="fas fa-envelope" aria-hidden="true"></i> <a href="mailto:tangyouyuan@hnu.edu.cn">tangyouyuan@hnu.edu.cn</a></span>
  </div>
  <div class="profile-links"><a href="https://github.com/Youyuan287"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a></div>
</div>

<div class="language-toggle" role="group" aria-label="Language selector">
  <button type="button" data-lang-switch="zh" class="is-active" aria-pressed="true">中文</button>
  <button type="button" data-lang-switch="en" aria-pressed="false">English</button>
</div>

<nav class="quick-nav" aria-label="Quick links">
  <a href="#about"><i class="fas fa-id-card" aria-hidden="true"></i><span class="lang-en">About</span><span class="lang-zh">个人简介</span></a>
  <a href="#research"><i class="fas fa-microscope" aria-hidden="true"></i><span class="lang-en">Research</span><span class="lang-zh">研究方向</span></a>
  <a href="#publications"><i class="fas fa-book-open" aria-hidden="true"></i><span class="lang-en">Publications</span><span class="lang-zh">代表论文</span></a>
  <a href="#education"><i class="fas fa-graduation-cap" aria-hidden="true"></i><span class="lang-en">Education</span><span class="lang-zh">教育经历</span></a>
  <a href="#contact"><i class="fas fa-envelope" aria-hidden="true"></i><span class="lang-en">Contact</span><span class="lang-zh">联系方式</span></a>
</nav>

<script>
(function () {
  var root = document.documentElement;
  function setLanguage(lang) {
    var next = lang === "en" ? "en" : "zh";
    root.setAttribute("data-lang", next);
    root.setAttribute("lang", next === "en" ? "en" : "zh-CN");
    document.querySelectorAll("[data-lang-switch]").forEach(function (button) {
      var active = button.getAttribute("data-lang-switch") === next;
      button.classList.toggle("is-active", active);
      button.setAttribute("aria-pressed", active ? "true" : "false");
    });
  }
  document.querySelectorAll("[data-lang-switch]").forEach(function (button) {
    button.addEventListener("click", function () { setLanguage(button.getAttribute("data-lang-switch")); });
  });
  setLanguage("zh");
}());
</script>

<hr>

<p><span class="anchor" id="about"></span></p>

# <i class="fas fa-id-card section-icon" aria-hidden="true"></i><span class="lang-en">About</span><span class="lang-zh">个人简介</span>

<p class="lang-en">I am <strong>Youyuan Tang</strong>, a Ph.D. student in Electronic Information at the School of Robotics and Artificial Intelligence, Hunan University, supervised by Prof. Hui Zhang.</p>
<p class="lang-zh">你好！我是<strong>唐友源</strong>，现为<strong>湖南大学人工智能与机器人学院</strong>电子信息博士研究生，导师为<strong>张辉教授</strong>。</p>
<p class="lang-en">My research focuses on 3D computer vision and intelligent perception, including point cloud semantic segmentation, open-vocabulary 3D scene understanding, open-world perception, and embodied perception.</p>
<p class="lang-zh">我的研究主要围绕<strong>三维计算机视觉与智能感知</strong>展开，关注点云语义分割、开放词汇三维场景理解、开放世界感知与具身感知等方向。</p>

<hr>

<p><span class="anchor" id="research"></span></p>

# <i class="fas fa-microscope section-icon" aria-hidden="true"></i><span class="lang-en">Research Directions</span><span class="lang-zh">研究方向</span>

<p class="lang-en">My research explores robust and generalizable 3D perception methods for complex real-world environments.</p>
<p class="lang-zh">面向复杂真实环境，研究鲁棒、可泛化的三维感知方法。</p>

<ul>
  <li><span class="lang-en">3D computer vision and point cloud semantic segmentation</span><span class="lang-zh">三维计算机视觉与点云语义分割</span></li>
  <li><span class="lang-en">Open-vocabulary 3D scene understanding</span><span class="lang-zh">开放词汇三维场景理解</span></li>
  <li><span class="lang-en">Open-world perception and embodied perception</span><span class="lang-zh">开放世界感知与具身感知</span></li>
</ul>

<hr>

<p><span class="anchor" id="publications"></span></p>

# <i class="fas fa-book-open section-icon" aria-hidden="true"></i><span class="lang-en">Selected Publications</span><span class="lang-zh">代表性论文</span>

<div class="paper-box">
  <div class="paper-box-image"><img src="assets/SAF.png" alt="SAF paper preview"></div>
  <div class="paper-box-text">
    <strong>SAF: A Structure-Aware Framework for Radial Ice Thickness Detection on Overhead Transmission Lines</strong><br>
    Hui Zhang, <strong>Youyuan Tang</strong>, Rui Du, Yihong Cao, Kaining Zhang, Yunkang Cao, Tongzhi Niu, Jianxu Mao, Yaonan Wang.<br>
    <em>IEEE Transactions on Industrial Informatics, 2026.</em><br>
    <a href="https://doi.org/10.1109/TII.2026.3659628">DOI</a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image"><img src="assets/AAS-CN-2025-0540-3.jpg" alt="Acta Automatica Sinica paper preview"></div>
  <div class="paper-box-text">
    <strong><span class="lang-zh">基于结构频谱感知框架的配电网点云语义分割</span><span class="lang-en">Semantic Segmentation of Distribution Network Point Clouds Based on a Structure Spectrum-Aware Framework</span></strong><br>
    <span class="lang-zh"><strong>唐友源</strong>, 张辉, 杜瑞, 张恺宁, 曹云康, 别克扎提·巴合提, 陈厚权, 王耀南。</span><span class="lang-en"><strong>Youyuan Tang</strong>, Hui Zhang, Rui Du, Kaining Zhang, Yunkang Cao, Biekezati Baheti, Houquan Chen, Yaonan Wang.</span><br>
    <em><span class="lang-zh">《自动化学报》, 2026, 52(4): 833–845。</span><span class="lang-en">Acta Automatica Sinica, 2026, 52(4): 833–845.</span></em><br>
    <a href="https://www.aas.net.cn/cn/article/doi/10.16383/j.aas.c250540?viewType=HTML"><span class="lang-zh">论文</span><span class="lang-en">Paper</span></a> · <a href="https://doi.org/10.16383/j.aas.c250540">DOI</a>
  </div>
</div>

<hr>

<p><span class="anchor" id="education"></span></p>

# <i class="fas fa-graduation-cap section-icon" aria-hidden="true"></i><span class="lang-en">Education</span><span class="lang-zh">教育经历</span>

<ul>
  <li><span class="lang-en">2026–Present, Ph.D. student in Electronic Information, School of Robotics and Artificial Intelligence, Hunan University. Supervisor: Prof. Hui Zhang.</span><span class="lang-zh">2026–至今，湖南大学人工智能与机器人学院电子信息博士研究生，导师：张辉教授。</span></li>
</ul>

<hr>

<p><span class="anchor" id="contact"></span></p>

# <i class="fas fa-envelope section-icon" aria-hidden="true"></i><span class="lang-en">Contact</span><span class="lang-zh">联系方式</span>

<p><a href="mailto:tangyouyuan@hnu.edu.cn">tangyouyuan@hnu.edu.cn</a> · <a href="https://github.com/Youyuan287">GitHub</a></p>
