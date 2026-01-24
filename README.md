# 🧪 CNPC-Lab Research Group Website

这是 **CNPC-Lab** 课题组/实验室网站的源代码仓库。
本网站基于 [Hugo](https://gohugo.io/) 和 [Wowchemy (Hugo Blox)](https://hugoblox.com/) 构建，托管于 GitHub，并由 Netlify 自动部署。

🌐 **访问网站**: [点击这里查看网站 (请替换为你的Netlify链接)](https://你的netlify链接.app)

---

## 📂 项目结构说明

核心文件夹的作用如下，修改内容主要在 `content` 文件夹中进行：

- **`content/`**: 存放所有的文章、人员介绍、论文数据。
  - `authors/`: 成员介绍（修改 admin 为你的信息）。
  - `publication/`: 发表的论文列表。
  - `post/`: 新闻动态或博客文章。
  - `event/`: 会议或讲座活动。
- **`static/`**: 存放图片、PDF等静态文件（引用时直接用 `/filename`）。
- **`config/`**: 网站的核心配置（如导航栏、网站标题等）。

---

## 🚀 如何更新网站 (常用命令备忘)

### 1. 本地预览
在 VS Code 终端中运行以下命令，可以在本地浏览器实时查看修改效果：
```bash
hugo server
