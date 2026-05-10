---
title: 实验平台与技术能力
type: landing

sections:
  # ============================================================
  # 1. 顶部横幅 (中石大红 · 极简艺术设计)
  # ============================================================
  - block: markdown
    content:
      text: |
        <div class="text-center d-flex flex-column align-items-center justify-content-center" 
             style="background: #ffffff; min-height: 280px; padding: 40px 20px; border-bottom: 1px solid #f0f0f0;">
          
          <h1 style="font-size: 3.2rem; font-weight: 900; color: #A6192E; letter-spacing: 8px; margin-bottom: 5px; font-family: 'Noto Serif SC', serif;">
            地震物理模型实验室
          </h1>
          
          <div style="width: 40px; height: 2px; background-color: #A6192E; margin: 20px auto;"></div>
          
          <p style="font-size: 1.1rem; color: #666; font-weight: 300; letter-spacing: 4px; margin-bottom: 35px;">
            多尺度物理模拟 <span style="color: #A6192E; font-weight: bold;">·</span> 复杂介质波场研究 <span style="color: #A6192E; font-weight: bold;">·</span> 智能化数据采集
          </p>
          
          <div style="font-size: 0.9rem;">
            <a href="/" style="color: #A6192E; text-decoration: none; border: 1.5px solid #A6192E; padding: 8px 30px; border-radius: 4px; font-weight: bold; transition: 0.3s; display: inline-block;"
               onmouseover="this.style.background='#A6192E'; this.style.color='#fff';" 
               onmouseout="this.style.background='transparent'; this.style.color='#A6192E';">
              <i class="fas fa-home mr-2"></i> 实验室首页
            </a>
          </div>

        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0', '0', '40px', '0']

  # ============================================================
  # 2. 核心技术装备 (4项 - 极简文字风)
  # ============================================================
  - block: markdown
    content:
      title: 核心技术装备
      subtitle: Advanced Equipment
      text: |
        <style>
          /* 统一极简卡片样式 */
          .text-feature-box { 
            transition: all 0.3s ease; 
            border-left: 4px solid #A6192E; 
            border-radius: 6px; 
            padding: 20px 15px; 
            background: #fff; 
            box-shadow: 0 2px 10px rgba(0,0,0,0.03);
            border: 1px solid #f2f2f2;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
          }
          .text-feature-box:hover { 
            transform: translateY(-4px); 
            box-shadow: 0 10px 20px rgba(166,25,46,0.08); 
          }
          .text-feature-box h6 { font-size: 1.05rem; font-weight: bold; margin-bottom: 6px; color: #333; }
          .text-feature-box p { font-size: 0.85rem; color: #777; margin: 0; line-height: 1.5; }
        </style>
        
        <div class="row g-3 mt-1">
          <div class="col-md-3 col-6">
            <div class="text-feature-box">
              <h6><i class="fas fa-microscope mr-2" style="color: #A6192E;"></i> 动静态弹性测试</h6>
              <p>涵盖伺服控制、高温高压及多场耦合测试系统</p>
            </div>
          </div>
          <div class="col-md-3 col-6">
            <div class="text-feature-box">
              <h6><i class="fas fa-satellite-dish mr-2" style="color: #A6192E;"></i> 三维高精度采集</h6>
              <p>智能化多轴水槽系统，实现高信噪比波场观测</p>
            </div>
          </div>
          <div class="col-md-3 col-6">
            <div class="text-feature-box">
              <h6><i class="fas fa-bolt mr-2" style="color: #A6192E;"></i> 超声激光测试</h6>
              <p>非接触式激光干涉技术，捕捉微观波场特征</p>
            </div>
          </div>
          <div class="col-md-3 col-6">
            <div class="text-feature-box">
              <h6><i class="fas fa-server mr-2" style="color: #A6192E;"></i> Bechlab 系统</h6>
              <p>国际先进的多场耦合动态监测与声波衰减研究</p>
            </div>
          </div>
        </div>
    design:
      css_class: "bg-light"
      spacing:
        padding: ['30px', '0', '15px', '0']

  # ============================================================
  # 3. 模型构建技术能力 (4项 - 极简文字风)
  # ============================================================
  - block: markdown
    content:
      title: 模型构建技术能力
      subtitle: Modeling Capabilities
      text: |
        <div class="row g-3 mt-1">
          <div class="col-md-3 col-6">
            <div class="text-feature-box">
              <h6><i class="fas fa-layer-group mr-2" style="color: #A6192E;"></i> 构造与层位模拟</h6>
              <p>精确还原褶皱、不整合面及复杂断裂网络形态</p>
            </div>
          </div>
          <div class="col-md-3 col-6">
            <div class="text-feature-box">
              <h6><i class="fas fa-mountain mr-2" style="color: #A6192E;"></i> 复杂储层模拟</h6>
              <p>针对砂岩扇体、碳酸盐岩缝洞等目标的精细构建</p>
            </div>
          </div>
          <div class="col-md-3 col-6">
            <div class="text-feature-box">
              <h6><i class="fas fa-braille mr-2" style="color: #A6192E;"></i> 各向异性介质</h6>
              <p>实现 VTI/HTI 等不同裂缝密度与分布参数的设计</p>
            </div>
          </div>
          <div class="col-md-3 col-6">
            <div class="text-feature-box">
              <h6><i class="fas fa-vial mr-2" style="color: #A6192E;"></i> 流体与含油气性</h6>
              <p>基于孔隙注入技术，模拟多相流体置换及 AVO 响应</p>
            </div>
          </div>
        </div>

        <div class="text-center mt-5">
          <a href="/equipment/detailes/" 
             style="display: inline-block; font-size: 0.95rem; color: #A6192E; border: 1.5px solid #A6192E; padding: 10px 35px; border-radius: 30px; text-decoration: none; font-weight: bold; transition: 0.3s;"
             onmouseover="this.style.background='#A6192E'; this.style.color='#fff';"
             onmouseout="this.style.background='transparent'; this.style.color='#A6192E';">
            查看实验室装备与技术详情 &rarr;
          </a>
        </div>
    design:
      spacing:
        padding: ['15px', '0', '40px', '0']

  # 3. 典型应用案例 (只显示 4 个最震撼的，其余放入详情页)
  - block: markdown
    content:
      title: 典型应用案例
      subtitle: Featured Case Studies
      text: |
        <style>
          .case-mini-card { border-radius: 8px; overflow: hidden; background: #fff; border: 1px solid #eee; transition: 0.3s; height: 100%; }
          .case-mini-card:hover { box-shadow: 0 10px 20px rgba(0,0,0,0.1); }
          .case-img { height: 160px; width: 100%; object-fit: cover; }
          .case-body { padding: 15px; }
        </style>
        <div class="row g-4">
          <div class="col-md-3">
            <div class="case-mini-card">
              <img src="/media/equipment/lab_example/example1.png" class="case-img">
              <div class="case-body">
                <h6 class="font-weight-bold">复杂构造与沉积扇体</h6>
                <a href="/equipment/cases/case1" class="small">查看实验数据 →</a>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="case-mini-card">
              <img src="/media/equipment/lab_example/example2.png" class="case-img">
              <div class="case-body">
                <h6 class="font-weight-bold">碳酸盐岩溶洞模型</h6>
                <a href="/equipment/cases/case2" class="small">查看实验数据 →</a>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="case-mini-card">
              <img src="/media/equipment/lab_example/example3-1.png" class="case-img">
              <div class="case-body">
                <h6 class="font-weight-bold">页岩气储层各向异性</h6>
                <a href="/equipment/cases/case3" class="small">查看实验数据 →</a>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="case-mini-card">
              <img src="/media/equipment/lab_example/example4.png" class="case-img">
              <div class="case-body">
                <h6 class="font-weight-bold">深海浊积扇体模拟</h6>
                <a href="/equipment/cases/case4" class="small">查看实验数据 →</a>
              </div>
            </div>
          </div>
        </div>
        <div class="text-center mt-5">
          <a href="/equipment/cases/" style="display: inline-block; padding: 12px 35px; background-color: #A6192E; color: white; font-weight: bold; border-radius: 30px; text-decoration: none; transition: 0.3s; box-shadow: 0 4px 15px rgba(166,25,46,0.3);">
          <i class="fas fa-folder-open mr-2"></i> 进入实验室案例库 (共 10 个)
          </a>
        </div>
    design:
      css_class: "bg-light"
      spacing:
        padding: ['40px', '0', '60px', '0']
---