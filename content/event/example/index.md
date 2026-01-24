---
# ==============================
# 基础信息设置
# ==============================
title: Example Event           # 事件/演讲标题 (例如："第25届地球物理年会" 或 "2025春季学期组会")

event: Wowchemy Conference     # 会议/活动名称 (例如："SEG 2024 Annual Meeting")
event_url: https://example.org # 会议官网链接 (可选)

# ==============================
# 地点设置
# ==============================
location: Wowchemy HQ          # 地点名称 (例如："教一楼 305 会议室" 或 "Zoom 线上")
address:                       # 详细地址 (如果是线上会议，或者是校内，这部分可以留空或删掉)
  street: 450 Serra Mall       # 街道
  city: Stanford               # 城市
  region: CA                   # 省/州
  postcode: '94305'            # 邮编
  country: United States       # 国家

summary: An example event.     # 简短摘要 (显示在首页或列表页的预览文字)
abstract: 'Lorem ipsum...'     # 详细摘要/简介 (支持 Markdown，可以写演讲的大纲或详细背景)

# ==============================
# 时间设置 (关键)
# 格式必须是：YYYY-MM-DDTHH:MM:SSZ (注意中间的 T 和最后的 Z)
# ==============================
date: '2030-06-01T13:00:00Z'      # 开始时间
date_end: '2030-06-01T15:00:00Z'  # 结束时间 (如果不想显示结束时间，可以在这一行前面加 # 注释掉)
all_day: false                    # 是否为全天活动 (true/false)

# 页面发布日期 (这不是演讲日期，而是这个页面在网站上显示的日期)
publishDate: '2017-01-01T00:00:00Z'

authors: []        # 演讲者/作者 (填写 content/authors/ 里的文件夹名，例如 ["admin", "zhang-san"])
tags: []           # 标签 (例如 ["地震反演", "学术报告"])

# ==============================
# 推荐设置
# ==============================
featured: false    # 是否为精选/置顶活动 (true 会显示在首页的 Featured 板块)

# ==============================
# 封面图设置
# ==============================
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right  # 图片裁剪重心 (Smart, Center, Top, Left, Right, Bottom)

# ==============================
# 资源链接按钮 (可选)
# 填上链接后，页面会自动生成对应的按钮。留空则不显示。
# ==============================
url_code: ''       # 相关代码链接
url_pdf: ''        # PDF 课件链接 (可将文件放在 static/files/ 下，填 'files/ppt.pdf')
url_slides: ''     # 幻灯片下载链接
url_video: ''      # 录像视频链接

# ==============================
# 关联 Markdown 幻灯片 (高级功能)
# ==============================
# 如果您用 Hugo 制作了网页版 PPT (在 content/slides/ 目录下)，这里填文件名。
# 如果没有，留空即可。
slides:

# ==============================
# 关联项目
# ==============================
# 如果这个演讲属于某个科研项目，这里填项目文件夹名。
projects:
---

Slides can be added in a few ways:
(幻灯片可以通过以下几种方式添加：)

- **Create** slides using Wowchemy's [_Slides_](https://docs.hugoblox.com/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
  (使用 Wowchemy 的 Slides 功能创建网页版 PPT，并在上面的 `slides` 参数中链接)
  
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
  (上传现有的 PPT/PDF 文件到 `static/` 文件夹，并在上面的 `url_slides` 参数中填入链接)
  
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/writing-markdown-latex/).
  (使用短代码直接在当前页面嵌入 Google Slides 或 Bilibili/YouTube 视频)

Further event details, including page elements such as image galleries, can be added to the body of this page.
(更多活动详情，包括相册等页面元素，都可以添加到这里。)