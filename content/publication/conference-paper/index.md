---
title: 'An example conference paper' # 论文标题

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: # 作者列表
  - admin # "admin" 对应你的用户名，会自动关联到你的个人主页
  - Robert Ford # 其他作者

# Author notes (optional)
author_notes: # 作者备注（选填）
  - 'Equal contribution' # 对应 admin：同等贡献（共一）
  - 'Equal contribution' # 对应 Robert Ford

date: '2013-07-01T00:00:00Z' # 论文实际发表日期
doi: '' # 论文的 DOI 号

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z' # 网页发布日期（用于排序，非论文发表时间）

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference'] # 出版物类型。
# 关键区别：这里填的是 'paper-conference' (会议论文)。
# 之前的期刊文章填的是 'article-journal'。

# Publication name and optional abbreviated publication name.
publication: In *Wowchemy Conference* # 会议全称 (例如：In IEEE CVPR 2013)
publication_short: In *ICW* # 会议简称 (例如：In CVPR)，列表页通常显示这个

abstract: Lorem ipsum dolor sit amet... # 摘要内容

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet... # 简短总结，用于搜索结果或列表预览。

tags: [] # 标签列表，例如 ['Deep Learning', 'NLP']

# Display this page in the Featured widget?
featured: true # 是否精选。
# 设为 true 后，这篇论文会出现在首页的 "Featured Publications" (精选出版物) 版块中，适合展示代表作。

# Custom links (uncomment lines below)
# links: # 自定义链接按钮（可选）
# - name: Custom Link
#   url: http://example.org

url_pdf: '' # PDF 下载链接
url_code: 'https://github.com/HugoBlox/hugo-blox-builder' # 代码链接
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder' # 数据集链接
url_poster: '' # 海报链接
url_project: '' # 项目主页链接
url_slides: '' # 幻灯片链接
url_source: 'https://github.com/HugoBlox/hugo-blox-builder' # 来源文档链接
url_video: 'https://youtube.com' # 视频演示链接

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image: # 封面图设置
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)' # 图片版权说明
  focal_point: '' # 图片焦点 (如 Center, Smart)
  preview_only: false # 是否仅预览。
  # false: 文章详情页顶部也会显示这张大图。
  # true: 只有在文章列表里能看到图，点进文章详情页不显示。

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: # 关联的项目
  - example # 对应 content/project/example/ 文件夹

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example # 关联的幻灯片文件 (content/slides/example/index.md)
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}
{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}
Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).