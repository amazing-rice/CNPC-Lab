---
title: home
date: 2025-01-01
type: landing

sections:
  # ============================================================
  # 1. 简洁轮播图
  # ============================================================
  - block: slider
    content:
      slides:
        - title: 地震物理模型实验室
          content: 高精度地球物理模拟 · 复杂油气储层成像
          align: center
          background:
            image:
              filename: teachers.jpg
              filters:
                brightness: 0.9
          link:
            text: 了解实验室
            url: "/publication/"
        - title: 地震物理模拟数据采集系统
          content: 工业级大型气浮三维自动采集系统
          align: center
          background:
            image:
              filename: 3wei shebei.jpg
              filters:
                brightness: 0.9
          link:
            text: 查看装备
            url: "/equipment/"
    design:
      slide_height: "40vh"
      is_fullscreen: false
      loop: true
      interval: 5000
      css_style: "max-width: 1200px; margin: 20px auto 0; border-radius: 12px; overflow: hidden; box-shadow: 0 10px 30px rgba(0,0,0,0.15);"

  # ============================================================
  # 2. 核心展示区：实验室概况 (左) + 基准数据集 (右)
  # ============================================================
  - block: markdown
    content:
      text: |
        <style>
          .split-container { display: flex; flex-wrap: wrap; gap: 30px; max-width: 1200px; margin: 0 auto; align-items: stretch; }
          .split-card { flex: 1; min-width: 320px; padding: 30px; background: #ffffff; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.04); border-top: 4px solid #A6192E; transition: transform 0.3s ease; }
          .split-card:hover { transform: translateY(-3px); box-shadow: 0 8px 25px rgba(166,25,46,0.08); }
          
          /* 标题样式 */
          .split-card h2 { color: #A6192E; font-size: 1.6rem; margin-top: 0; margin-bottom: 5px; font-weight: bold; border-bottom: none;}
          .split-card .sub-title { font-size: 0.9rem; color: #777; margin-bottom: 20px; padding-bottom: 12px; border-bottom: 1px solid #f0f0f0; }
          
          /* 左侧文字样式 */
          .left-content p { margin-bottom: 10px; line-height: 1.6; font-size: 0.95rem; color: #444; }
          .left-content ul { padding-left: 20px; margin-bottom: 20px; }
          .left-content li { margin-bottom: 6px; line-height: 1.5; font-size: 0.95rem; color: #444; }
          
          /* 右侧列表样式 */
          .right-content ul { list-style: none; padding-left: 0; margin: 0; }
          .right-content li { margin-bottom: 15px; line-height: 1.5; font-size: 0.95rem; color: #444; background: #fdf8f8; padding: 15px; border-radius: 8px; border-left: 3px solid #A6192E; }
          .right-content li strong { color: #A6192E; display: block; margin-bottom: 4px; font-size: 1.05rem; }
        </style>

        <div class="split-container">
          
          <div class="split-card left-content">
            <h2>实验室概况</h2>
            <div class="sub-title">中国石油大学（北京） · 油气资源与工程全国重点实验室</div>
            <p>本实验室专注于深层复杂油气储层的地震物理模拟与成像技术研究。团队汇聚了多位行业资深专家、合作院校院长及客座教授，构建了从物理模型设计到工业应用的完整科研体系。</p>
            <p style="margin-top: 15px; color: #222;"><strong>依托核心实验设备，我们能做什么：</strong></p>
            <ul>
              <li><strong>定制化物理建模：</strong>高精度制作各类常规与非常规油气储层（如裂缝性页岩气等）及复杂构造的三维实体物理模型。</li>
              <li><strong>高保真波场采集：</strong>依托大型气浮三维自动系统，开展宽/窄方位、多尺度三维地震物理模拟数据采集。</li>
              <li><strong>算法与机理验证：</strong>为全波形反演(FWI)、各向异性介质成像、AI数据处理等前沿算法提供基准验证。</li>
              <li><strong>岩石物理测试：</strong>开展复杂介质波传播机理实验，精确反映微裂缝、流体等对地震波的响应特征。</li>
            </ul>
            <a href="/people/" style="display: inline-block; color: #A6192E; font-weight: bold; text-decoration: none; font-size: 0.95rem; border-bottom: 1px solid #A6192E; padding-bottom: 2px;">查看完整专家与团队名单 →</a>
          </div>

          <div class="split-card right-content">
            <h2>独家模型与基准数据</h2>
            <div class="sub-title">依托智能化实验平台，赋能勘探前沿算法验证</div>
            <ul>
              <li>
                <strong>🎯 复杂构造三维波场数据集</strong>
                基于高精度三维水槽系统采集。涵盖深层逆掩断裂、潜山及断陷盆地等复杂构造的高信噪比基准波场，是验证前沿偏移算法的试金石。
              </li>
              <li>
                <strong>🎯 页岩气储层及各向异性数据集</strong>
                构建包含不同裂缝密度的泸州页岩气工区模型。输出的波场数据可精确反映微裂缝对地震波速度及振幅的响应，支撑甜点预测。
              </li>
              <li>
                <strong>🎯 沉积扇与宽窄方位对比数据集</strong>
                针对河道砂体与三维冲积扇体，提供不同观测系统（宽/窄方位）下的高保真偏移成像数据，为目标成像质量评价提供依据。
              </li>
            </ul>
          </div>
          
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["40px", "0", "15px", "0"]
      background:
        color: "#fdf2f2" # 整体浅粉底色，凸显白色卡片

  # ============================================================
  # 3. 核心设备与实验能力简述 (三个图标作为底部基座)
  # ============================================================
  - block: features
    content:
      items:
        - name: 装备：三维物理模型系统
          description: 大型气浮全自动高精度水槽采集平台
          icon: microscope
          icon_pack: fas
          link: "/equipment/"
        - name: 实验：复杂构造波场模拟
          description: 断陷盆地、潜山等高难度实体建模与观测
          icon: layer-group
          icon_pack: fas
        - name: 应用：AI与算法试金石
          description: 为行业前沿智能反演与成像提供基准数据
          icon: brain
          icon_pack: fas
    design:
      columns: "3"
      spacing:
        padding: ["10px", "0", "40px", "0"] 
      background:
        color: "#fdf2f2" # 底色与上方模块保持一致，融为一体

# ============================================================
  # 3. 核心装备与特色能力 (图文并茂，四个一行)
  # ============================================================
  - block: markdown
    content:
      title: "<span style='color: #A6192E; font-size: 1.8rem;'>核心装备与特色能力</span>"
      subtitle: "<span style='font-size: 1rem;'>融合顶尖设备与精湛工艺，打造深层油气探测物理模拟基准</span>"
      text: |
        <style>
          .core-adv-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 20px; margin-top: 30px; }
          .adv-card { background: #fff; padding: 15px; border-radius: 8px; border-top: 3px solid #A6192E; box-shadow: 0 4px 15px rgba(0,0,0,0.04); transition: transform 0.3s; display: flex; flex-direction: column; }
          .adv-card:hover { transform: translateY(-5px); box-shadow: 0 8px 25px rgba(166,25,46,0.1); border-color: #d12e45; }
          /* 图片容器与样式 */
          .adv-img-box { width: 100%; height: 150px; border-radius: 6px; overflow: hidden; margin-bottom: 15px; background: #f8f9fa; }
          .adv-img-box img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.5s ease; }
          .adv-card:hover .adv-img-box img { transform: scale(1.08); }
          /* 标题与描述 */
          .adv-title { font-size: 1.05rem; font-weight: bold; color: #222; margin-bottom: 10px; text-align: center; }
          .adv-desc { font-size: 0.88rem; color: #555; line-height: 1.6; margin-bottom: 0; text-align: justify; }
          
          /* 响应式设计：平板变两列，手机变一列 */
          @media (max-width: 992px) { .core-adv-grid { grid-template-columns: repeat(2, 1fr); } }
          @media (max-width: 576px) { .core-adv-grid { grid-template-columns: 1fr; } }
        </style>

        <div class="core-adv-grid">
          <div class="adv-card">
            <div class="adv-img-box"><img src="/media/equipment/eq_3d_acq.jpg" alt="三维高精度采集"></div>
            <div class="adv-title">三维气浮高精度采集</div>
            <p class="adv-desc">依托旗舰级大型气浮智能化水槽系统，实现极高定位精度的三维物理模拟，获取超高信噪比基准数据。</p>
          </div>
          <div class="adv-card">
            <div class="adv-img-box"><img src="/media/equipment/eq_bechlab.jpg" alt="多场耦合测试"></div>
            <div class="adv-title">多场耦合动静态测试</div>
            <p class="adv-desc">结合国际先进的 Bechlab 等系统，真实复现深层极端温压与应力环境，开展流体置换与衰减机理研究。</p>
          </div>
          <div class="adv-card">
            <div class="adv-img-box"><img src="/media/equipment/sim_cave.jpg" alt="缝洞储层模拟"></div>
            <div class="adv-title">复杂地质目标体构建</div>
            <p class="adv-desc">突破材料与工艺极限，高精度还原深层碳酸盐岩缝洞系统、逆掩断裂及复杂河道砂体等三维实体模型。</p>
          </div>
          <div class="adv-card">
            <div class="adv-img-box"><img src="/media/equipment/sim_fracture_photo.jpg" alt="各向异性介质"></div>
            <div class="adv-title">各向异性与流体模拟</div>
            <p class="adv-desc">精确控制裂缝密度构建 HTI/VTI 介质，结合孔隙注入技术，实现微观流体动态响应及 AVO 特性验证。</p>
          </div>
        </div>
        
        <div style="text-align: center; margin-top: 30px;">
          <a href="/equipment/" style="font-size: 0.95rem; color: #A6192E; font-weight: bold; text-decoration: none; border-bottom: 1px solid #A6192E; padding-bottom: 2px;">查看装备详情与典型模型案例 →</a>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["30px", "0", "40px", "0"]
      background:
        color: "#fdf2f2"

  # ============================================================
  # 5. 产学研合作单位 (纯净 Logo 墙 - 强制单行自适应)
  # ============================================================
  - block: markdown
    content:
      title: "<span style='color: #A6192E; font-size: 1.8rem;'>产学研合作单位</span>"
      text: |
        <style>
          .logo-wall-clean { 
            display: flex; 
            flex-wrap: nowrap; /* 核心修改：强制不换行，保持在同一行 */
            justify-content: space-between; /* 核心修改：让它们均匀分布，撑满两边 */
            align-items: center; 
            gap: 20px; /* 缩小硬性间距，把空间留给图片放大 */
            max-width: 1200px; /* 充分利用网页的宽度 */
            margin: 20px auto 0; 
            padding: 20px 0;
          }
          .logo-item { 
            flex: 1; /* 核心修改：让5个Logo自动均分这一行的宽度 */
            max-width: 230px; /* 限制一下最大尺寸，依然非常大 */
            height: 100px; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
            transition: transform 0.3s ease;
          }
          /* 鼠标悬停时微微放大 */
          .logo-item:hover {
            transform: scale(1.8); 
          }
          .logo-item img { 
            max-width: 100%; 
            max-height: 100%; 
            object-fit: contain; /* 保证 Logo 原比例不拉伸 */
          }
          
          /* 手机和平板端保护：屏幕太小（如手机）时允许换行，防止挤到看不清 */
          @media (max-width: 992px) {
            .logo-wall-clean { flex-wrap: wrap; justify-content: center; gap: 30px; }
            .logo-item { flex: none; width: 150px; height: 70px; }
          }
        </style>

        <div class="logo-wall-clean">
          <div class="logo-item"><img src="/media/logos/cnpc.png" alt="中国石油"></div>
          <div class="logo-item"><img src="/media/logos/sinopec.png" alt="中国石化"></div>
          <div class="logo-item"><img src="/media/logos/cnooc.png" alt="中国海油"></div>
          <div class="logo-item"><img src="/media/logos/bgp.png" alt="东方物探"></div>
          <div class="logo-item"><img src="/media/logos/hfut.png" alt="合肥工业大学"></div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["30px", "0", "40px", "0"]
      background:
        color: "#ffffff"

  # ============================================================
  # 6. 技术合作与服务 (清爽明亮风格)
  # ============================================================
  - block: markdown
    content:
      text: |
        <div style="text-align: center;">
          <h2 style="color: #A6192E; margin-bottom: 12px; font-weight: bold;">🤝 联合攻关与数据共享</h2>
          <p style="font-size: 1.05em; margin-bottom: 25px; color: #555555; max-width: 700px; margin-left: auto; margin-right: auto;">
            我们秉持开放理念，提供<strong>定制物理模型、基准数据获取、波场机理分析</strong>等技术服务，助力学术研究与解决复杂油气勘探难题。
          </p>
          <a href="/contact/" style="display: inline-block; padding: 12px 35px; background-color: #A6192E; color: #ffffff; font-weight: bold; border-radius: 30px; text-decoration: none; box-shadow: 0 4px 15px rgba(166, 25, 46, 0.25); transition: all 0.2s ease;" onmouseover="this.style.transform='translateY(-2px)'; this.style.boxShadow='0 6px 20px rgba(166, 25, 46, 0.35)';" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 4px 15px rgba(166, 25, 46, 0.25)';">
            <i class="fas fa-envelope mr-1"></i> 探讨合作 / 申请数据
          </a>
        </div>
    design:
      columns: "1"
      background:
        color: "#fdf8f8" # 极浅的暖灰/微粉底色，显得干净且有层次
      spacing:
        padding: ["50px", "0", "50px", "0"]

  # ============================================================
  # 7. 近期成果概览 (按要求移动到最底层)
  # ============================================================
  - block: collection
    content:
      title: "<span style='color: #A6192E;'>近期成果</span>"
      count: 3 
      filters:
        folders:
          - publication
      text: |
        <div style="text-align: right; margin-top: -15px;"><a href="/publication/" style="color: #A6192E; font-weight: bold; text-decoration: none;">查看全部成果 >></a></div>
    design:
      view: citation  
      columns: "1"
      spacing:
        padding: ["40px", "0", "40px", "0"]
      background:
        color: "#fdf8f8" 
---