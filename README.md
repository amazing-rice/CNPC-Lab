<<<<<<< HEAD
# 地震物理模型实验室 (CNPC-Lab) 官方网站

这是 **中国石油大学（北京）地震物理模型实验室 - 丁拼搏课题组** 的官方网站源代码仓库。本网站旨在展示实验室的研究成果、核心技术成果、实验平台装备以及团队动态。

## 🌟 核心功能

* **学术成果展示**：集成近年代表性论文列表，支持 DOI 跳转与详情页深度阅读。
* **实验平台介绍**：详细展示大型气浮三维地震物理模型实验系统及配套装备。
* **动态新闻发布**：记录实验室重大活动、学术交流及领导访问（如“部长参观”等）。
* **团队成员看板**：展示课题组导师及研究生团队信息。
* **响应式设计**：基于 Hugo Blox 框架，适配 PC、平板与手机端。

## 🛠️ 技术栈

* **框架**: [Hugo](https://gohugo.io/) (Static Site Generator)
* **主题**: [Hugo Blox Builder](https://hugoblox.com/) (原 Academic 主题)
* **部署**: [Netlify](https://www.netlify.com/) (自动化持续集成)
* **版本控制**: Git / GitHub

## 📂 目录结构说明

根据项目截图，核心目录逻辑如下：

=======
---

# 地震物理模型实验室 (CNPC-Lab) 官方网站

这是 **中国石油大学（北京）地震物理模型实验室 - 丁拼搏课题组** 的官方网站源代码仓库。本网站旨在展示实验室的研究成果、核心技术成果、实验平台装备以及团队动态。

## 🌟 核心功能

* **学术成果展示**：集成近年代表性论文列表，支持 DOI 跳转与详情页深度阅读。
* **实验平台介绍**：详细展示大型气浮三维地震物理模型实验系统及配套装备。
* **动态新闻发布**：记录实验室重大活动、学术交流及领导访问（如“部长参观”等）。
* **团队成员看板**：展示课题组导师及研究生团队信息。
* **响应式设计**：基于 Hugo Blox 框架，适配 PC、平板与手机端。

## 🛠️ 技术栈

* **框架**: [Hugo](https://gohugo.io/) (Static Site Generator)
* **主题**: [Hugo Blox Builder](https://hugoblox.com/) (原 Academic 主题)
* **部署**: [Netlify](https://www.netlify.com/) (自动化持续集成)
* **版本控制**: Git / GitHub

## 📂 目录结构说明

根据项目截图，核心目录逻辑如下：

>>>>>>> 09ccb71 (优化网站SEO检索描述)
```text
CNPC-Lab/
├── config/_default/          # 网站核心配置文件
│   ├── languages.yaml       # 多语言及浏览器标题设置
│   ├── menus.yaml           # 顶部导航栏菜单定义
│   ├── params.yaml          # 网站基本信息（Logo、SEO、页脚）
│   └── hugo.yaml            # Hugo 全局配置
├── content/                 # 网站所有文字内容
│   ├── post/                # 实验室新闻动态（如：部长参观、中石油访问）
│   ├── publication/         # 学术论文详情页（如：2024各向异性研究、2025裂缝预测）
│   │   ├── papers/          # 论文列表页
│   │   └── rewards/         # 核心技术详情页
│   ├── equipment/           # 实验平台与装备介绍
│   ├── people/              # 团队成员信息
│   └── authors/             # 个人详情配置（含个人头像 avatar.jpg）
├── static/media/            # 静态媒体资源
│   ├── database/            # 数据库相关图片
│   ├── equipment/           # 设备展示图
│   └── publication_picture/ # 论文配图（如：lab_system.png）
├── assets/media/            # 主题相关媒体资源（Logo、轮播图背景）
├── netlify.toml             # Netlify 部署脚本配置文件
└── README.md                # 项目说明文档

```

## 🚀 快速开始

### 1. 本地开发环境搭建

确保你已经安装了 [Hugo Extended 版本](https://gohugo.io/installation/)。

```bash
# 克隆仓库
git clone https://github.com/amazing-rice/CNPC-Lab.git

# 进入目录
cd CNPC-Lab

# 启动本地实时预览服务器
hugo server

```

访问 `http://localhost:1313` 即可查看预览。

### 2. 更新内容

* **添加论文**: 在 `content/publication/` 下新建文件夹，参考现有项目放置 `index.md` 和 `featured.png`。
* **发布新闻**: 在 `content/post/` 下新建文件夹，命名格式推荐为 `YYYY-MM-DD-title`。

## ☁️ 部署与维护

本项目已实现 **Git-Ops 自动化部署**：

1. 本地修改代码或内容。
2. 执行 Git 提交：
```bash
git add .
git commit -m "更新了XX论文详情"
git push origin main

```


3. GitHub 收到推送后，**Netlify** 会自动触发构建并在 1 分钟内完成全网更新。

## 📧 联系我们

* **实验室名称**: 地震物理模型实验室 (中石油勘探开发研究院-中国石油大学联合实验室)
* **所在单位**: 中国石油大学（北京）
* **课题组**: 丁拼搏教授课题组

---

<<<<<<< HEAD
*© 2026 地震物理模型实验室 | Built with Love and Science.*
=======
*© 2026 地震物理模型实验室 | Built with Love and Science.*
>>>>>>> 09ccb71 (优化网站SEO检索描述)
