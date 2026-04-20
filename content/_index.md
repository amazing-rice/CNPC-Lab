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
              filename: welcome.jpg
              filters:
                brightness: 0.4
          link:
            text: 了解实验室
            url: "/people/"
        - title: 自动化数据采集平台
          content: 工业级大型气浮三维自动采集系统
          align: center
          background:
            image:
              filename: welcome.jpg
              filters:
                brightness: 0.4
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
  # 5. 独家物理模型与基准数据展示 (图片压扁，移除内嵌CTA)
  # ============================================================
  - block: markdown
    content:
      title: "<span style='color: #A6192E;'>独家基准数据与物理模型</span>"
      subtitle: "依托大型物理模拟平台，提供高保真地震波场数据，赋能算法验证与前沿机理研究。"
      text: |
        <div class="row text-center mt-3">
          <div class="col-md-4 mb-3">
            <div class="card h-100 shadow-sm" style="border-radius: 8px; border: none; overflow: hidden; transition: transform 0.3s ease;" onmouseover="this.style.transform='translateY(-3px)';" onmouseout="this.style.transform='translateY(0)';">
              <img src="/media/welcome.jpg" style="height: 150px; object-fit: cover;" alt="缝洞体数据">
              <div class="card-body" style="padding: 1.2rem;">
                <h6 style="font-weight: bold; color: #333;">深层缝洞体波场数据集</h6>
                <p class="text-muted" style="font-size: 0.85em; margin-top: 8px; margin-bottom: 0;">
                  包含不同溶洞尺度的高信噪比物理模拟数据，是验证复杂构造成像算法的绝佳测试集。
                </p>
              </div>
            </div>
          </div>
          
          <div class="col-md-4 mb-3">
            <div class="card h-100 shadow-sm" style="border-radius: 8px; border: none; overflow: hidden; transition: transform 0.3s ease;" onmouseover="this.style.transform='translateY(-3px)';" onmouseout="this.style.transform='translateY(0)';">
              <img src="/media/welcome.jpg" style="height: 150px; object-fit: cover;" alt="各向异性数据">
              <div class="card-body" style="padding: 1.2rem;">
                <h6 style="font-weight: bold; color: #333;">各向异性与裂缝模型数据</h6>
                <p class="text-muted" style="font-size: 0.85em; margin-top: 8px; margin-bottom: 0;">
                  涵盖不同介质的超声波透射与反射基准数据，用于验证横波分裂与方位各向异性理论。
                </p>
              </div>
            </div>
          </div>
          
          <div class="col-md-4 mb-3">
            <div class="card h-100 shadow-sm" style="border-radius: 8px; border: none; overflow: hidden; transition: transform 0.3s ease;" onmouseover="this.style.transform='translateY(-3px)';" onmouseout="this.style.transform='translateY(0)';">
              <img src="/media/welcome.jpg" style="height: 150px; object-fit: cover;" alt="多分量数据">
              <div class="card-body" style="padding: 1.2rem;">
                <h6 style="font-weight: bold; color: #333;">3D 多分量 (P/SV/SH) 数据集</h6>
                <p class="text-muted" style="font-size: 0.85em; margin-top: 8px; margin-bottom: 0;">
                  采用自研新型换能器采集的纯净多分量基准数据，支撑多波联合反演与岩性流体识别。
                </p>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["30px", "0", "40px", "0"]
      background:
        color: "#fdf2f2" 

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
            <i class="fas fa-envelope mr-1"></i> 探讨合作 / 申请数据
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