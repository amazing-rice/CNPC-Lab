---
title: home
date: 2025-01-01
type: landing

sections:
# ============================================================
# 1. 简洁轮播图 - 突出实验室定位
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
    slide_height: "60vh"
    is_fullscreen: false
    loop: true
    interval: 5000

# ============================================================
# 2. 实验室简介 - 简短核心介绍
# ============================================================
- block: markdown
  content:
    title: 实验室概况
    subtitle: 中国石油大学（北京） · 油气资源与工程全国重点实验室
    text: |
      **狄帮让教授团队**专注于深层复杂油气储层的地震物理模拟与成像技术研究。

      构建了从物理模型设计到工业应用的完整科研体系，已为行业提供**50+项**技术解决方案。

      [了解更多 →](/people/)
  design:
    spacing:
      padding: ["60px", "0", "60px", "0"]
    background:
      color: "#f9f7f7"

# ============================================================
# 3. 核心能力展示 - 三张简洁卡片
# ============================================================
- block: features
  content:
    title: 核心能力
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
      padding: ["0", "0", "80px", "0"]

# ============================================================
# 4. 近期成果概览 - 简洁展示
# ============================================================
- block: collection
  content:
    title: 近期成果
    count: 5  # 因为变紧凑了，可以多展示几个，改成了 5
    filters:
      folders:
        - publication
    text: |
      [查看全部成果 →](/publication/)
  design:
    view: citation  # 🔴 关键修改：改成 citation (标准学术引用格式)，不显示大图
    columns: "1"    # 🔴 关键修改：单列显示，最符合论文阅读习惯
    spacing:
      padding: ["60px", "0", "60px", "0"]
    background:
      color: "#f9f7f7"

# ============================================================
# 5. 合作与服务 - 明确价值主张
# ============================================================
- block: markdown
  content:
    text: |
      ## 技术合作与服务

      我们提供**物理模型实验、波场机理分析、技术咨询**等服务，助力解决复杂油气勘探难题。

      [联系我们 →](/contact/)
  design:
    columns: "1"
    background:
      color: "#2c3e50"
      text_color_light: true
    spacing:
      padding: ["50px", "0", "50px", "0"]
---