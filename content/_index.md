---
title: home
date: 2025-01-01
type: landing

sections:

# ============================================================
# 1. Hero Slider（70% 高度 + 半透明遮罩）
# ============================================================
- block: slider
  content:
    slides:
      - title: 地震物理模型实验室
        content: >
          聚焦复杂油气储层探测与成像技术
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.4
        link:
          text: 探索实验室
          url: "#about"

      - title: 核心技术体系
        content: >
          高精度地球物理模拟与数据采集
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.4
        link:
          text: 技术详情
          url: /equipment/

      - title: 智能地球物理
        content: >
          AI在地震数据处理与解释中的应用
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.4
        link:
          text: 了解更多
          url: /event/

      - title: 团队科研人员
        content: >
          精英团队，跨学科协作
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.4
        link:
          text: 团队详情
          url: /people/

      - title: 近年成果
        content: >
          论文、出版物及科研成果展示
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.4
        link:
          text: 查看成果
          url: /publication/
  design:
    slide_height: "60vh"
    is_fullscreen: false
    loop: true
    interval: 5000

# ============================================================
# 2. 三亮点卡片（核心科研方向）
# ============================================================
- block: features
  content:
    title: 我们的核心优势
    subtitle: Core Strengths
    items:
      - name: 复杂构造物理模拟
        description: 高陡构造、断裂系统、沉积体三维物理建模
        icon: layer-group
        icon_pack: fas
      - name: 弹性波传播机理
        description: 各向异性与裂缝介质中的波场响应特征
        icon: wave-square
        icon_pack: fas
      - name: 自动化数据采集
        description: 大型气浮三维模型高精度自动采集系统
        icon: microchip
        icon_pack: fas
  design:
    columns: "3"
    background:
      color: "#f9f7f7"
    spacing:
      padding: ['60px', '0', '60px', '0']

# ============================================================
# 3. 实验室概况（Markdown）
# ============================================================
- block: markdown
  id: about
  content:
    title: 实验室概况
    text: |
      依托**中国石油大学（北京）油气资源与工程全国重点实验室**，本实验室致力于地球物理前沿问题研究与深层油气勘探关键技术攻关。

      实验室由**狄帮让教授**创立，长期聚焦地震波传播机理、复杂构造物理模拟及岩石物理实验研究。
      围绕深层、复杂油气储层的成像与表征难题，构建了从**物理模型设计—数据采集—机理分析—方法验证**的完整科研体系。
  design:
    spacing:
      padding: ['80px', '0', '40px', '0']

# ============================================================
# 4. 实验室规模统计（Features）
# ============================================================
- block: features
  content:
    items:
      - name: 成立时间
        description: "**2010 年**"
        icon: calendar
        icon_pack: fas
      - name: 科研项目
        description: "**50+ 项**"
        icon: flask
        icon_pack: fas
      - name: 团队规模
        description: "**30+ 人**"
        icon: users
        icon_pack: fas
  design:
    columns: "3"
    background:
      color: "#f9f7f7"
    spacing:
      padding: ['0', '0', '80px', '0']

# ============================================================
# 5. 核心技术体系（Features）
# ============================================================
- block: features
  content:
    title: 核心技术体系
    items:
      - name: 岩石物理实验
        description: 高温高压条件下岩石物性测试
        icon: microscope
        icon_pack: fas
      - name: 全波形反演
        description: 基于物理模型数据的高精度反演研究
        icon: code-branch
        icon_pack: fas
      - name: 智能地球物理
        description: 深度学习在地震数据处理与解释中的应用
        icon: brain
        icon_pack: fas
  design:
    columns: "3"
    background:
      color: "#f9f7f7"
    spacing:
      padding: ['60px', '0', '60px', '0']

# ============================================================
# 6. 近年成果（Portfolio）
# ============================================================
- block: portfolio
  content:
    title: 代表性成果
    filters:
      folders:
        - publication
  design:
    view: masonry
    columns: "3"
    spacing:
      padding: ['80px', '0', '60px', '0']

# ============================================================
# 7. 新闻动态（Collection）
# ============================================================
- block: collection
  content:
    title: 新闻动态
    count: 3
    filters:
      folders:
        - post
  design:
    view: card
    columns: "3"
    spacing:
      padding: ['60px', '0', '80px', '0']

# ============================================================
# 8. 底部号召（Call to Action）
# ============================================================
- block: markdown
  content:
    text: |
      ## 加入我们，探索地球深部奥秘

      欢迎对**地球物理、物理模拟与智能方法**感兴趣的优秀学子加入团队。

      [联系我们](/contact/)
  design:
    columns: '1'
    background:
      image:
        filename: equipment/device01.jpg
        filters:
          brightness: 0.3
      text_color_light: true
    spacing:
      padding: ['100px', '0', '100px', '0']

---
