# 🧪 CNPC-Lab Research Group Website

这是 **CNPC-Lab (地震物理模型实验室)** 课题组网站的源代码仓库。
本网站基于 [Hugo](https://gohugo.io/) 和 [Hugo Blox (原 Wowchemy)](https://hugoblox.com/) 框架构建，托管于 GitHub，并由 Netlify 自动进行全球分发与部署。

🌐 **访问网站**: [https://cnpc-lab.netlify.app/](https://cnpc-lab.netlify.app/)

---

## 📂 项目结构说明

网站的核心配置与内容均位于 `content/` 文件夹内，主要结构如下：

- **`content/`**: 所有的文字内容与页面逻辑。
  - `_index.md`: **首页内容**（轮播图、实验室概况、核心能力、数据展示模块等）。
  - `people/`: 课题组成员信息（导师及学生介绍）。
  - `publication/`: **科研成果**。包含带图的代表作文件夹（如 `2025-jge-torsional-wave`）和 `_index.md` 中的完整论文列表。
  - `equipment/`: **实验平台与典型案例**。展示实验室硬件装备与独家基准数据集。
  - `event/`: 学术活动、奖项与课题组动态。
  - `contact/`: 联系方式与数据获取申请说明。
- **`static/media/`**: 存放图片（波场快照、实验照片）、PDF 等静态资源。
- **`config/`**: 网站全局配置（导航栏菜单、标题、页脚信息等）。

---

## 🚀 开发与更新指南

### 1. 本地实时预览
在修改内容后，打开 VS Code 终端运行以下命令，即可在 `localhost:1313` 实时预览效果：
```bash
hugo server
