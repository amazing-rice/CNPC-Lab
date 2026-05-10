---
title: 科研实力与成果概览
header:
  image: ""
  caption: ""
---

<style>
/* ----------------------------------------------------
   1. 系统默认元素隐藏
   ---------------------------------------------------- */
/* ❗彻底隐藏 Hugo 系统自带的搜索框、过滤器、默认论文列表等冗余元素 */
.form-row, .pub-filters, .search-container,
.pub-list, .media.stream-item {
  display: none !important;
}

/* ----------------------------------------------------
   2. 顶部三大“核心能力”卡片样式 (.custom-card)
   ---------------------------------------------------- */
.custom-card {
  border: none;
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.custom-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 30px rgba(166,25,46,0.15) !important;
}
.custom-card .card-body {
  padding: 15px 15px 12px 15px !important; /* 卡片内部紧凑排版 */
}
.custom-card .card-title {
  font-size: 1rem !important; 
  color: #A6192E; 
  font-weight: bold;
  margin-bottom: 8px !important; 
}
.custom-card .card-text {
  font-size: 0.8rem !important; 
  color: #666;
  line-height: 1.4 !important; 
  margin-bottom: 12px !important; 
}

/* ----------------------------------------------------
   3. 全局按钮统一样式 (.btn-red, .btn-outline-red)
   ---------------------------------------------------- */
.btn-red {
  background-color: #A6192E; color: white; border: none;
  padding: 4px 10px !important; font-size: 0.8rem !important;
}
.btn-red:hover { background-color: #8A1525; color: white; }

.btn-outline-red {
  color: #A6192E; border: 1px solid #A6192E; background-color: transparent;
  padding: 4px 10px !important; font-size: 0.8rem !important;
}
.btn-outline-red:hover { background-color: #A6192E; color: white; }

.btn-icon { display: flex; align-items: center; justify-content: center; gap: 6px; }

/* ----------------------------------------------------
   4. 底部“近年代表作” 2x2 论文卡片样式 (.my-pub-card)
   ---------------------------------------------------- */
.my-pub-card { 
  border: none; border-radius: 10px; background: #fff; display: flex; flex-direction: row; 
  height: 180px; overflow: hidden; text-decoration: none !important; color: inherit !important; 
  margin-bottom: 20px; box-shadow: 0 2px 8px rgba(0,0,0,0.04); transition: all 0.3s ease;
}
.my-pub-card:hover { transform: translateY(-6px) scale(1.01); box-shadow: 0 12px 24px rgba(166,25,46,0.12); }
.my-pub-img { flex: 0 0 35%; background: #fafafa; display: flex; align-items: center; justify-content: center; padding: 10px; }
.my-pub-img img { max-height: 100%; max-width: 100%; object-fit: contain; }
.my-pub-text { flex: 1; padding: 15px 20px; display: flex; flex-direction: column; justify-content: center; }
.my-pub-title { font-size: 0.98rem; font-weight: 600; color: #1a1a1a; margin-bottom: 6px; line-height: 1.35; }
.my-pub-author { font-size: 0.85rem; color: #666; margin-bottom: 10px; }
.my-pub-tag { font-size: 0.75rem; color: #A6192E; font-weight: bold; background: #f8f8f8; padding: 3px 8px; border-radius: 12px; display: inline-block; }
</style>


<div class="row" style="margin-bottom: 50px;">
  <div class="col-12 text-center mb-4">
    <h2 style="color: #333; font-weight: bold;">权威物理模拟数据与核心技术</h2>
    <p class="text-muted">依托自主研发的工业级物理模拟系统，提供高信噪比基准数据与复杂构造成像方案</p>
  </div>

  <div class="col-md-4 mb-4">
    <div class="card custom-card h-100">
      <div style="height: 180px; overflow: hidden;">
        <img src="/media/publication_picture/lab_system.png" class="card-img-top" style="object-fit: cover; height: 100%;">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">高精度三维物理模拟技术</h5>
        <p class="card-text">综合考量多种地质因素构建三维模型，精准刻画构造形态、断裂裂缝分布及地层弹性参数，提供精度显著高于传统数值模拟的波场数据。</p>
        <a href="/equipment/#data-gallery" class="btn btn-outline-red btn-sm btn-icon mt-auto">了解物理模拟优势</a>
      </div>
    </div>        
  </div>

  <div class="col-md-4 mb-4">
    <div class="card custom-card h-100">
      <div style="height: 180px; overflow: hidden;">
        <img src="/media/publication_picture/image.png" class="card-img-top" style="object-fit: cover; height: 100%;">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">全流程实验与综合解决方案</h5>
        <p class="card-text">覆盖“模型设计-制作-高信噪比采集-处理解释”全套技术流程。全面赋能非常规致密油气、天然气水合物勘探以及CCUS地球物理监测。</p>
        <a href="/equipment/#imaging" class="btn btn-outline-red btn-sm btn-icon mt-auto">查看技术流程详情</a>
      </div>
    </div>
  </div>

  <div class="col-md-4 mb-4">
    <div class="card custom-card h-100">
      <div style="height: 180px; overflow: hidden;">
        <img src="/media/publication_picture/corporate-collaboration.png" class="card-img-top" style="object-fit: cover; height: 100%;">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">企业横向合作案例</h5>
        <p class="card-text">已承担中石油、中石化等企业级重大攻关项目50余项，实现产学研深度融合。</p>
        <a href="/contact/" class="btn btn-red btn-sm btn-icon mt-auto">寻求项目合作</a>
      </div>
    </div>
  </div>
</div>

<hr style="border-top: 1px dashed #ddd; margin: 40px 0;">


<div class="row text-center mb-5">
  <div class="col-md-4 mb-3">
    <h2 style="color: #A6192E; font-weight: bold;">130+</h2>
    <p class="font-weight-bold" style="color: #555;">高水平学术论文</p>
  </div>
  <div class="col-md-4 mb-3">
    <h2 style="color: #d39e00; font-weight: bold;">50+</h2>
    <p class="font-weight-bold" style="color: #555;">国家发明专利</p>
  </div>
  <div class="col-md-4 mb-3">
    <h2 style="color: #2c3e50; font-weight: bold;">10+</h2>
    <p class="font-weight-bold" style="color: #555;">国家级纵向课题</p>
  </div>
</div>

<div class="row">
  <div class="col-md-6 mb-4">
    <h4 style="border-left: 4px solid #d39e00; padding-left: 10px; margin-bottom: 20px;">🏆 权威科技奖励</h4>
    <ul class="fa-ul" style="color: #444; line-height: 1.8;">
      <li class="mb-2"><span class="fa-li"><i class="fas fa-trophy text-warning"></i></span><strong>教育部高等学校科学研究优秀成果一等奖</strong> (2023)</li>
      <li class="mb-2"><span class="fa-li"><i class="fas fa-trophy text-warning"></i></span><strong>中国产学研合作创新成果一等奖</strong> (2019)</li>
      <li class="mb-2"><span class="fa-li"><i class="fas fa-award text-secondary"></i></span><strong>国家科技进步二等奖</strong> (2014, 参与)</li>
    </ul>
  </div>

  <div class="col-md-6 mb-4">
    <h4 style="border-left: 4px solid #A6192E; padding-left: 10px; margin-bottom: 20px;">📌 重大科研项目</h4>
    <ul class="fa-ul" style="color: #444; line-height: 1.8;">
      <li class="mb-2"><span class="fa-li"><i class="fas fa-check-circle" style="color: #A6192E;"></i></span><strong>国家自然科学基金</strong>：裂缝介质横波传播机理研究</li>
      <li class="mb-2"><span class="fa-li"><i class="fas fa-check-circle" style="color: #A6192E;"></i></span><strong>国家科技重大专项</strong>：多波地震勘探配套技术</li>
      <li class="mb-2"><span class="fa-li"><i class="fas fa-briefcase text-secondary"></i></span><strong>企业横向攻关</strong>：深层碳酸盐岩缝洞体物理模拟</li>
    </ul>
    <a href="/publication/rewards/" class="btn btn-link p-0" style="color: #A6192E; font-weight: bold;">查看获奖和科研项目详情 &rarr;</a>
  </div>
</div>

<hr style="border-top: 2px solid #eee; margin-top: 40px;">


<div class="text-center mt-5 mb-4">
  <h3 style="color: #A6192E; font-weight: bold;">📚 实验室近年核心代表作</h3>
</div>

<div class="row mb-5">
  <div class="col-md-6">
    <a href="/publication/2025-cgj-fracture-prediction/" class="my-pub-card">
      <div class="my-pub-img"><img src="/publication/2025-cgj-fracture-prediction/featured.png"></div>
      <div class="my-pub-text">
        <div class="my-pub-title">利用物理模拟地震数据验证基于方位各向异性的裂缝预测方法</div>
        <div class="my-pub-author">刘恩良 等</div>
        <div class="my-pub-tag">2025 · 地球物理学报</div>
      </div>
    </a>
  </div>

  <div class="col-md-6">
    <a href="/publication/2025-jge-torsional-wave/" class="my-pub-card">
      <div class="my-pub-img"><img src="/publication/2025-jge-torsional-wave/featured.png"></div>
      <div class="my-pub-text">
        <div class="my-pub-title">Comparison of Torsional and SH Waves in Anisotropic Media</div>
        <div class="my-pub-author">Ding et al.</div>
        <div class="my-pub-tag">2025 · JGE</div>
      </div>
    </a>
  </div>

  <div class="col-md-6">
    <a href="/publication/2024-jge-fracture-characterization/" class="my-pub-card">
      <div class="my-pub-img"><img src="/publication/2024-jge-fracture-characterization/featured.png"></div>
      <div class="my-pub-text">
        <div class="my-pub-title">Fracture characterization using seismic physical modeling</div>
        <div class="my-pub-author">Liu et al.</div>
        <div class="my-pub-tag">2024 · JGE</div>
      </div>
    </a>
  </div>

  <div class="col-md-6">
    <a href="/publication/2024-geophysics-multicomponent/" class="my-pub-card">
      <div class="my-pub-img"><img src="/publication/2024-geophysics-multicomponent/featured.png"></div>
      <div class="my-pub-text">
        <div class="my-pub-title">Seismic response of P, SV, SH waves via physical modeling</div>
        <div class="my-pub-author">Ding et al.</div>
        <div class="my-pub-tag">2024 · GEOPHYSICS</div>
      </div>
    </a>
  </div>
</div>

<div class="text-center mt-4 mb-5">
  <a href="/publication/papers" style="padding: 10px 30px; background-color: #fdf2f2; color: #A6192E; border: 2px solid #A6192E; border-radius: 30px; text-decoration: none;">
    查看全部论文 →
  </a>
</div>