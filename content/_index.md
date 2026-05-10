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
      # 微调：上边距缩小到 20px
      css_style: "max-width: 1200px; margin: 20px auto 0; border-radius: 12px; overflow: hidden; box-shadow: 0 10px 30px rgba(0,0,0,0.15);"

  # ============================================================
  # 2. 实验室简介 (大幅缩减下方留白)
  # ============================================================
  - block: markdown
    content:
      title: "<span style='color: #A6192E;'>实验室概况</span>"
      subtitle: "中国石油大学（北京） · 油气资源与工程全国重点实验室"
      text: |
        **狄帮让教授团队**专注于深层复杂油气储层的地震物理模拟与成像技术研究。构建了从物理模型设计到工业应用的完整科研体系，已为行业提供 **50+项** 技术解决方案。

        <div style="margin-top: 10px;"><a href="/people/" style="color: #A6192E; font-weight: bold; text-decoration: none; border-bottom: 1px solid #A6192E;">了解更多团队信息 →</a></div>
    design:
      spacing:
        padding: ["30px", "0", "0px", "0"] # 核心修改：底部 padding 改为 0
      background:
        color: "#fdf2f2" 

  # ============================================================
  # 3. 核心能力展示 (与上方简介紧密衔接)
  # ============================================================
  - block: features
    content:
      # 移除重复的大标题，让其作为简介的延伸
      items:
        - name: 物理模拟
          description: 复杂构造三维建模与波场分析
          icon: layer-group
          icon_pack: fas
          link: "/equipment/"
        - name: 方法研究
          description: 各向异性介质成像与全波形反演
          icon: wave-square
          icon_pack: fas
          link: "/publication/"
        - name: 智能应用
          description: AI辅助地震数据处理与解释
          icon: brain
          icon_pack: fas
          link: "/event/"
    design:
      columns: "3"
      spacing:
        padding: ["20px", "0", "30px", "0"]
      background:
        color: "#fdf2f2" # 核心修改：背景色与上方统一，形成一个大模块

  # ============================================================
  # 4. 近期成果概览
  # ============================================================
  - block: collection
    content:
      title: "<span style='color: #A6192E;'>近期成果</span>"
      count: 3  # 核心修改：改为 3 篇，节省垂直空间
      filters:
        folders:
          - publication
      text: |
        <div style="text-align: right; margin-top: -15px;"><a href="/publication/" style="color: #A6192E; font-weight: bold; text-decoration: none;">查看全部成果 >></a></div>
    design:
      view: citation  
      columns: "1"
      spacing:
        padding: ["30px", "0", "20px", "0"]
      background:
        color: "#ffffff" # 改回纯白背景，形成视觉层次

  # ============================================================
  # 5. 独家物理模型与基准数据 (真实 PPT 数据版)
  # ============================================================
  - block: markdown
    content:
      title: "<span style='color: #A6192E;'>独家物理模型与基准数据集</span>"
      subtitle: "依托大型智能化实验平台，输出高保真地震波场数据，赋能勘探算法验证与前沿机理研究。"
      text: |
        <style>
        .data-card { background: #fff; border-radius: 8px; border: 1px solid #f0f0f0; overflow: hidden; transition: 0.3s; height: 100%; box-shadow: 0 4px 10px rgba(0,0,0,0.02); }
        .data-card:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(166,25,46,0.08); border-color: #f5c6cb; }
        .data-img-box { height: 160px; overflow: hidden; position: relative; background: #e9ecef; display: flex; align-items: center; justify-content: center; }
        .data-img-box img { width: 100%; height: 100%; object-fit: cover; }
        .data-card-body { padding: 20px; }
        .data-card-body h5 { color: #A6192E; font-size: 1.1rem; font-weight: bold; margin-bottom: 10px; }
        .data-card-body p { color: #666; font-size: 0.9rem; line-height: 1.6; margin-bottom: 0; }
        </style>

        <div class="row g-4 mt-3">
        <div class="col-md-4">
        <div class="data-card">
        <div class="data-img-box">
        <img src="/media/equipment/lab_example/example10-1.png" alt="复杂构造三维波场数据集">
        </div>
        <div class="data-card-body">
        <h5>复杂构造三维波场数据集</h5>
        <p>基于高精度三维水槽系统采集。涵盖深层逆掩断裂、潜山及断陷盆地等复杂构造的高信噪比基准波场，是验证前沿高精度偏移成像算法的试金石。</p>
        </div>
        </div>
        </div>

        <div class="col-md-4">
        <div class="data-card">
        <div class="data-img-box">
        <img src="/media/equipment/lab_example/example1.png" alt="非常规储层岩石物理数据集">
        </div>
        <div class="data-card-body">
        <h5>页岩气储层及各向异性数据集</h5>
        <p>构建包含不同裂缝密度的泸州页岩气工区模型。输出的波场数据可精确反映微裂缝对地震波速度及振幅的响应，支撑各向异性反演与甜点预测。</p>
        </div>
        </div>
        </div>

        <div class="col-md-4">
        <div class="data-card">
        <div class="data-img-box">
        <img src="/media/equipment/lab_example/example3-2.png" alt="河道砂体及宽窄方位数据集">
        </div>
        <div class="data-card-body">
        <h5>沉积扇与宽窄方位对比数据集</h5>
        <p>针对河道砂体与三维冲积扇体，提供不同观测系统（宽/窄方位）下的高保真偏移成像数据，为地震采集脚印分析与目标成像质量评价提供直观依据。</p>
        </div>
        </div>
        </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["40px", "0", "60px", "0"]
      background:
        color: "#fdf8f8"

  # ============================================================
  # 6. 合并后的技术合作与服务 (二合一)
  # ============================================================
  - block: markdown
    content:
      text: |
        <div style="text-align: center;">
          <h2 style="color: white; margin-bottom: 12px; font-weight: bold;">🤝 联合攻关与数据共享</h2>
          <p style="font-size: 1.05em; margin-bottom: 20px; color: #f8f9fa; max-width: 700px; margin-left: auto; margin-right: auto;">
            我们秉持开放理念，提供<strong>定制物理模型、基准数据获取、波场机理分析</strong>等技术服务，助力学术研究与解决复杂油气勘探难题。
          </p>
          <a href="/contact/" style="display: inline-block; padding: 10px 30px; background-color: #ffffff; color: #A6192E; font-weight: bold; border-radius: 30px; text-decoration: none; box-shadow: 0 4px 10px rgba(0,0,0,0.15); transition: transform 0.2s;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
            <i class="fas fa-envelope mr-1"></i> 探讨合作 / 申请数据 / 加入我们
          </a>
        </div>
    design:
      columns: "1"
      background:
        color: "rgba(166, 25, 46, 0.9)"
        text_color_light: true
      spacing:
        padding: ["40px", "0", "40px", "0"]
---