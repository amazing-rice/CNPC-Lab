---
title: "An example journal article" # 文章标题
authors: # 作者列表
- admin # "admin" 通常指代网站拥有者（你自己），会自动链接到你的个人简介
- Robert Ford # 其他合著者名字
author_notes: # 作者备注（选填，与上方的 authors 一一对应）
- "Equal contribution" # 对应 admin 的备注：同等贡献
- "Equal contribution" # 对应 Robert Ford 的备注
date: "2015-09-01T00:00:00Z" # 论文实际发表的日期
doi: "" # 数字对象唯一标识符 (Digital Object Identifier)，填入后会自动生成链接

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z" # 网页发布日期（用于定时发布或排序，这通常不是论文发表日期，而是你把这篇论文传到网站上的时间）

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"] # 出版物类型。
# 常用值：
# "article-journal" (期刊文章)
# "paper-conference" (会议论文)
# "thesis" (学位论文)
# "report" (报告)
# 格式必须是列表 ["..."]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)" # 出版物全称（如期刊名、会议名），支持 Markdown 格式（如斜体）
publication_short: "" # 出版物简称（可选），如果填了，在列表页可能会优先显示简称

abstract: Lorem ipsum dolor sit amet... # 摘要内容。支持 Markdown，但建议保持纯文本以免格式混乱。

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet... # 总结。这是摘要的简短版本，通常用于网站首页或列表页的预览。如果不填，默认截取摘要的前几行。

tags: # 标签，用于文章分类和搜索
- Source Themes
featured: false # 是否为精选文章。设为 true 时，文章会显示在首页的 "Featured" 版块或置顶。

# links: # 自定义链接部分（可选）
# - name: "" # 链接显示的文字
#   url: "" # 链接地址
url_pdf: http://arxiv.org/pdf/1512.04133v1 # PDF 下载链接，对应页面上的 "PDF" 按钮
url_code: 'https://github.com/HugoBlox/hugo-blox-builder' # 代码仓库链接，对应 "Code" 按钮
url_dataset: '' # 数据集链接
url_poster: '' # 海报链接
url_project: '' # 项目链接
url_slides: '' # 幻灯片链接
url_source: '' # 来源链接
url_video: '' # 视频链接

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image: # 封面图片设置
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)' # 图片说明/版权来源（支持 Markdown）
  focal_point: "" # 图片焦点。例如 "Smart", "Center", "TopLeft" 等，用于自动裁剪时保留重点。
  preview_only: false # 是否仅在预览列表中显示。
  # false: 文章详情页顶部也会显示大图。
  # true: 只有在文章列表页能看到缩略图，点进文章后不显示大图。

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [] # 关联项目。填写 content/project/ 文件夹下的项目文件名（不带扩展名）。关联后，该项目页面下会自动显示这篇论文。

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example # 关联幻灯片。填写 content/slides/ 文件夹下的文件名。页面会出现 "Slides" 按钮。
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}
Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).