---
title: "典型应用案例库"
date: 2026-05-10
type: page
summary: "实验室 10 个代表性物理模拟实验案例，提供从模型设计到波场分析的全流程展示。"
---

<style>
/* ----------------------------------------------------
   🔥 终极安全宽屏方案：直接拓宽主题底层容器，绝不破坏页脚
   ---------------------------------------------------- */
.article-container, 
.article-style,
.container {
  max-width: 1000px !important;
}

/* ----------------------------------------------------
   1. 卡片核心样式
   ---------------------------------------------------- */
.custom-card {
  border: none;
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.03);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  background-color: #fff;
}
.custom-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 30px rgba(166,25,46,0.12) !important;
}
.custom-card .card-body {
  padding: 20px !important; 
}
.custom-card .card-title {
  font-size: 1.15rem !important; 
  color: #111; 
  font-weight: bold;
  margin-bottom: 12px !important; 
  line-height: 1.4;
}
.custom-card .card-text {
  font-size: 0.95rem !important; 
  color: #666;
  line-height: 1.6 !important; 
  margin-bottom: 20px !important; 
  text-align: justify;
}

/* ----------------------------------------------------
   2. 按钮样式
   ---------------------------------------------------- */
.btn-outline-red {
  color: #A6192E; border: 1px solid #A6192E; background-color: transparent;
  padding: 6px 15px !important; font-size: 0.9rem !important;
  border-radius: 20px; font-weight: bold; transition: 0.3s; text-align: center;
}
.btn-outline-red:hover { background-color: #A6192E; color: white; text-decoration: none;}

/* ----------------------------------------------------
   3. 页面专属优化
   ---------------------------------------------------- */
.cases-intro { 
  color: #555; font-size: 1.05rem; line-height: 1.8; margin-bottom: 40px; 
  background: #fdfaf6; padding: 20px 25px; border-radius: 8px; border-left: 4px solid #A6192E; 
}
.img-wrapper {
  height: 240px; /* 保证科研图片展示空间 */
  background: #fafafa;
  display: flex; align-items: center; justify-content: center;
  border-bottom: 1px solid #f0f0f0; padding: 10px;
}
.img-wrapper img {
  max-height: 100%; max-width: 100%; object-fit: contain; transition: transform 0.4s ease;
}
.custom-card:hover .img-wrapper img {
  transform: scale(1.03);
}
</style>

<div style="padding: 10px 0;">

<div class="cases-intro">
实验室具备构建各类复杂地质目标体的核心能力，能够精确模拟地下介质的几何形态与物理属性。以下图册展示了实验室近年来完成的 10 个代表性物理模拟实验案例，点击卡片即可查看详细的模型参数、实验设计及波场原始数据。
</div>

<div class="row">

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example1.png" alt="复杂构造与沉积扇体模拟">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">1. 复杂构造与沉积扇体模拟</h5>
        <p class="card-text">针对深层复杂断裂带及岩性油气藏（沉积扇体）的成像难题，构建三维精细物理模型，验证高精度偏移成像算法对构造及扇体边缘的刻画能力。</p>
        <a href="/equipment/cases/case1/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example2.png" alt="碳酸盐岩溶洞模型">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">2. 碳酸盐岩溶洞模型</h5>
        <p class="card-text">通过特殊工艺构建尺度可控的溶洞网络，模拟碳酸盐岩储层典型的“串珠”状反射及杂乱波场特征，为缝洞型储层定量雕刻提供基准。</p>
        <a href="/equipment/cases/case2/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example3-1.png" alt="页岩气储层各向异性模拟">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">3. 页岩气储层各向异性模拟</h5>
        <p class="card-text">制作包含不同裂缝密度的 VTI/HTI 各向异性物理模型，研究层理与天然裂缝对纵横波传播速度及衰减的综合影响。</p>
        <a href="/equipment/cases/case3/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example4.png" alt="深海浊积扇体模拟">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">4. 深海浊积扇体模拟</h5>
        <p class="card-text">模拟崎岖海底地形与深水速度梯度，刻画深海浊积岩的尖灭与透镜体细节，为海上宽频宽方位地震采集设计提供物理验证。</p>
        <a href="/equipment/cases/case4/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example5-1.png" alt="火山岩储层物理模拟">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">5. 火山岩储层物理模拟</h5>
        <p class="card-text">构建强波阻抗差异的火山岩相模型，研究火山喷发机构、岩相分带及内部孔缝系统的复杂地震波场散射与绕射特征。</p>
        <a href="/equipment/cases/case5/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example6-1.png" alt="煤层气储层裂缝模拟">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">6. 煤层气储层裂缝模拟</h5>
        <p class="card-text">精确控制裂缝密度与张开度，模拟薄互层背景下的含气煤层地震响应，为煤层气富集区的 AVO 分析与甜点预测提供依据。</p>
        <a href="/equipment/cases/case6/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example7.png" alt="盐丘构造物理模拟">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">7. 盐丘构造物理模拟</h5>
        <p class="card-text">构建复杂的高速盐丘刺穿模型，研究盐丘侧翼陡倾角断层及盐下隐蔽构造的波场阴影区照明问题。</p>
        <a href="/equipment/cases/case7/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example8-1.png" alt="致密砂岩气藏模拟">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">8. 致密砂岩气藏模拟</h5>
        <p class="card-text">通过孔隙流体注入实验，分析不同含气饱和度下致密砂岩的地震波频散与衰减规律，助力致密气藏的流体识别。</p>
        <a href="/equipment/cases/case8/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example9.png" alt="断陷盆地层序模拟">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">9. 断陷盆地层序模拟</h5>
        <p class="card-text">模拟箕状断陷盆地的多期次沉积演化与多级断裂系统，研究复杂层序地层格架下的地震同相轴追踪与断层精细解释。</p>
        <a href="/equipment/cases/case9/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

  <div class="col-lg-4 col-md-6 mb-4">
    <div class="card custom-card h-100">
      <div class="img-wrapper">
        <img src="/media/equipment/lab_example/example10-1.png" alt="潜山油气藏物理模拟">
      </div>
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">10. 潜山油气藏物理模拟</h5>
        <p class="card-text">构建古地貌潜山及内部风化壳裂缝带模型，验证叠前深度偏移技术对潜山内幕复杂反射的成像效果。</p>
        <a href="/equipment/cases/case10/" class="btn btn-outline-red btn-sm mt-auto">查看详情及数据 &rarr;</a>
      </div>
    </div>
  </div>

</div>

<div class="text-center" style="margin-top: 40px; margin-bottom: 20px;">
  <a href="/equipment/" class="btn btn-outline-red" style="padding: 10px 30px !important; border-width: 2px;">
    &larr; 返回实验平台主页
  </a>
</div>

</div>