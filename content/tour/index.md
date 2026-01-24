---
title: Tour        # 页面标题：在浏览器标签和菜单中显示的名称
date: 2025-10-24

type: landing      # 页面类型：Landing (落地页)，表示这是一个由组件堆叠而成的页面

sections:
  # ==============================
  # 核心组件：Slider (轮播图/幻灯片)
  # ==============================
  - block: slider
    content:
      # --- 幻灯片列表 ---
      slides:
      
      # [第一张幻灯片]
      - title: 👋 Welcome to the group         # 标题：欢迎来到课题组
        content: Take a look at what we're working on... # 副标题/描述文字
        align: center                          # 文字对齐方式：center (居中), left (居左), right (居右)
        background:
          image:
            # 图片文件名：请将图片放在 assets/media/ 文件夹下
            filename: coders.jpg
            filters:
              brightness: 0.7                  # 图片亮度：0.7 表示压暗 30%，为了让白色的文字看得更清楚
          position: right                      # 图片对齐重心
          color: '#666'                        # 如果图片加载失败，显示的背景颜色
      
      # [第二张幻灯片]
      - title: Lunch & Learn ☕️                # 标题：午餐研讨会 (建议改为：学术交流 / 组会)
        content: 'Share your knowledge with the group...' # 描述：分享知识...
        align: left                            # 文字居左
        background:
          image:
            filename: contact.jpg              # 背景图
            filters:
              brightness: 0.7
          position: center
          color: '#555'

      # [第三张幻灯片] - 带按钮的
      - title: World-Class Semiconductor Lab   # 标题：世界级半导体实验室 (【注意】请改为：地震物理模型实验室)
        content: 'Just opened last month!'     # 描述：上个月刚开放 (建议改为：拥有先进的物理模拟设施)
        align: right                           # 文字居右
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5                  # 0.5 比较暗，文字会很明显
          position: center
          color: '#333'
        
        # 按钮配置 (Call to Action)
        link:
          icon: graduation-cap                 # 图标：这是 FontAwesome 图标名 (如 graduation-cap, envelope)
          icon_pack: fas                       # 图标库类型
          text: Join Us                        # 按钮文字：加入我们
          url: ../contact/                     # 跳转链接：../contact/ 表示跳转到联系页面

    # --- 轮播图整体设计设置 ---
    design:
      # 幻灯片高度：留空表示自动适应
      slide_height: ''
      
      # 是否全屏：true 表示轮播图会占据整个屏幕的高度 (非常有视觉冲击力)
      is_fullscreen: true
      
      # 是否自动播放：true (自动轮播), false (需要手动点)
      loop: false
      
      # 自动播放间隔：单位是毫秒 (2000 = 2秒)
      interval: 2000
---