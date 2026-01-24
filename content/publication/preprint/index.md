---
title: "An example preprint / working paper" # 论文标题
authors: # 作者列表
- admin # 对应你的用户名
date: "2019-04-07T00:00:00Z" # 写作日期或上传到预印本平台的日期
doi: "" # 如果预印本平台（如 arXiv 或 OSF）提供了 DOI，可以在这里填入

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z" # 网页发布/排序日期

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"] # 出版物类型
# 关键点：这里使用的是 "article"。
# 在 Hugo Blox 默认设置中，"article" 类型通常显示为 "Preprint" (预印本) 或 "General Article"。
# 这与 "article-journal" (期刊) 和 "paper-conference" (会议) 有所区别。

# Publication name and optional abbreviated publication name.
publication: "" # 出版物名称。
# 因为是预印本或工作论文，通常还没有发表在特定期刊上，所以这里通常留空。
# 或者你可以填 "arXiv", "Submitted to Journal X", "Under Review" 等说明状态。
publication_short: "" # 简称，留空即可。

abstract: Lorem ipsum dolor sit amet... # 摘要

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet... # 总结/简介

tags: # 标签
- Source Themes
featured: false # 是否精选

links: # 自定义链接按钮（这是本示例的一个特色）
- name: Custom Link # 按钮上显示的文字（例如 "Demo", "Project Page"）
  url: http://example.org # 点击按钮跳转的地址
url_pdf: http://arxiv.org/pdf/1512.04133v1 # PDF 链接（通常填 arXiv 的 PDF 链接）
url_code: 'https://github.com/HugoBlox/hugo-blox-builder' # 代码链接
url_dataset: '#' # 数据集
url_poster: '#' # 海报
url_project: '' # 项目
url_slides: '' # 幻灯片
url_source: '#' # 来源/源文件
url_video: '#' # 视频

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image: # 封面图设置
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: # 关联项目
- internal-project # 对应 content/project/internal-project/

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example # 关联幻灯片
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).