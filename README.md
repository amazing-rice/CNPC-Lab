# 地震物理模型实验室 (CNPC-Lab) 官方网站

> 🔗 **在线预览站点**：https://cnpc-lab.netlify.app/

这是 **中国石油大学（北京）地震物理模型实验室 - 丁拼搏课题组** 的官方网站源代码仓库。网站用于集中展示实验室研究成果、核心技术成果、实验平台设备与团队动态，服务于学术合作与对外宣传。

## ✨ 核心功能
- **学术成果展示**：整合近年代表性论文列表，支持 DOI 跳转与详情页深度阅读
- **实验平台介绍**：详细呈现大型气浮三维地震物理模型实验系统及配套设备
- **动态新闻发布**：记录实验室重大活动、学术交流、来访访问等重要动态
- **团队成员看板**：展示课题组导师及研究生团队的个人信息与研究方向
- **全端响应式设计**：基于 Hugo Blox 框架构建，完美适配 PC、平板与移动端

## 🛠️ 技术栈
- **站点框架**：[Hugo](https://gohugo.io/) — 高性能静态站点生成器
- **主题体系**：[Hugo Blox Builder](https://hugoblox.com/) — 原 Academic 主题，结构化内容框架
- **自动部署**：[Netlify](https://www.netlify.com/) — Git 驱动的持续集成与全球 CDN 分发
- **版本控制**：Git / GitHub

## 📂 目录结构
```text
CNPC-Lab/
├── config/_default/          # 网站核心配置目录
│   ├── languages.yaml       # 多语言配置与页面标题设置
│   ├── menus.yaml           # 顶部导航栏菜单定义
│   ├── params.yaml          # 站点基础参数（Logo、SEO、页脚信息）
│   └── hugo.yaml            # Hugo 全局运行配置
├── content/                 # 站点所有内容源文件（Markdown）
│   ├── post/                # 实验室新闻动态
│   ├── publication/         # 学术成果与技术详情
│   │   ├── papers/          # 论文列表页
│   │   └── rewards/         # 核心技术成果详情页
│   ├── equipment/           # 实验平台与设备介绍
│   ├── people/              # 团队成员概览
│   └── authors/             # 成员个人详情配置（含头像等资源）
├── static/media/            # 静态媒体资源
│   ├── database/            # 数据相关配图
│   ├── equipment/           # 设备展示图片
│   └── publication_picture/ # 论文与成果配图
├── assets/media/            # 主题相关媒体资源（Logo、轮播背景等）
├── layouts/partials/        # 自定义页面组件
├── netlify.toml             # Netlify 构建与部署配置
├── theme.toml               # 主题配置文件
└── README.md                # 项目说明文档
```

## 🚀 快速开始

### 1. 本地开发环境
前置依赖：安装 **Hugo Extended 版本**（安装指引：[官方文档](https://gohugo.io/installation/)）

```bash
# 克隆仓库
git clone https://github.com/amazing-rice/CNPC-Lab.git

# 进入项目目录
cd CNPC-Lab

# 启动本地实时预览服务
hugo server
```

启动后访问 `http://localhost:1313` 即可实时预览站点效果。

### 2. 内容更新指南
- **新增论文**：在 `content/publication/` 下新建独立文件夹，参考现有格式放入 `index.md` 与封面图 `featured.png`
- **发布新闻**：在 `content/post/` 下新建文件夹，命名推荐使用 `YYYY-MM-DD-标题标识` 格式

## ☁️ 自动化部署
项目已配置 Git-Ops 自动化部署流程，推送代码即可自动更新线上站点，预览地址为：https://cnpc-lab.netlify.app/

1. 本地完成内容或代码修改
2. 提交并推送至主分支：
```bash
git add .
git commit -m "更新内容：XXX"
git push origin main
```
3. GitHub 收到推送后，Netlify 将自动触发构建，通常 1 分钟内完成全站更新。

## 📬 联系我们
- **实验室全称**：地震物理模型实验室（中石油勘探开发研究院-中国石油大学联合实验室）
- **依托单位**：中国石油大学（北京）
- **负责课题组**：丁拼搏教授课题组

---

© 2026 地震物理模型实验室 | Built with Hugo & Hugo Blox
