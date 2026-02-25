# Feynman 个人博客

这是一个个人博客网站项目，基于 GitHub Pages 部署。

## 📝 项目简介

Feynman 是一名爱编程的焦化方向硕士生的个人博客，用于分享编程知识、技术笔记和生活感悟。

- **网站地址**：https://blog.midlight.top/
- **作者**：Feynman
- **构建方式**：GitHub Pages 静态网站

## 🌟 功能特性

- 📚 文章归档和分类管理
- 🏷️ 标签系统快速检索
- 🎨 响应式设计，支持浅色/深色主题切换
- 🔍 本地搜索功能
- 🎵 音乐播放模块
- 📊 访问统计和阅读数据
- 💬 评论功能集成

## 📂 项目结构

```
FeynmanNddbb.github.io/
├── index.html              # 首页
├── about/                  # 关于页面
├── archives/               # 文章归档
├── tags/                   # 标签页面
├── 2025/                   # 2025年文章目录
├── assets/                 # 页面资源
├── css/                    # 样式文件
├── js/                     # 脚本文件
├── img/                    # 图片资源
├── music/                  # 音乐文件
├── page/                   # 其他页面
├── CNAME                   # 自定义域名配置
├── sitemap.xml             # 网站地图
├── robots.txt              # 搜索引擎配置
└── 404.html                # 404 页面
```

## 🚀 快速开始

### 环境要求
- Node.js v14 或更高版本
- Git

### 本地运行

1. **克隆项目**
```bash
git clone https://github.com/FeynmanNddbb/FeynmanNddbb.github.io.git
cd FeynmanNddbb.github.io
```

2. **启动本地服务器**
```bash
# 使用 Node.js 的 http-server
npx http-server -p 8080

# 或使用 Python（Python 3）
python -m http.server 8080

# 或使用 Python 2
python -m SimpleHTTPServer 8080
```

3. **访问网站**
在浏览器中打开：http://localhost:8080

## ✏️ 修改和开发

### 编辑内容
- **首页内容**：编辑 `index.html`
- **关于页面**：编辑 `about/` 目录下的文件
- **样式修改**：编辑 `css/index.css`
- **脚本修改**：编辑 `js/` 目录下的文件

### 发布更新

1. 在本地修改和测试
2. 提交更改
```bash
git add .
git commit -m "描述你的修改"
```

3. 推送到 GitHub
```bash
git push origin main
```

> GitHub Pages 将自动部署到 https://blog.midlight.top/

## 📱 主要模块

| 模块 | 描述 |
|------|------|
| **首页** | 展示最新文章和网站概览 |
| **文章归档** | 按时间组织的所有文章列表 |
| **标签系统** | 按主题分类的文章导航 |
| **关于页面** | 个人介绍和联系方式 |
| **搜索功能** | 本地文章内容搜索 |
| **评论系统** | 读者交流和反馈 |
| **音乐模块** | 音乐播放列表展示 |

## 🛠️ 技术栈

- **前端框架**：原生 HTML5 + CSS3 + JavaScript
- **样式框架**：自定义 CSS
- **图标库**：Font Awesome
- **CDN**：jsDelivr
- **部署方案**：GitHub Pages

## 📄 文件说明

- **CNAME**：配置自定义域名 `blog.midlight.top`
- **sitemap.xml**：SEO网站地图
- **robots.txt**：搜索引擎爬虫配置
- **baidusitemap.xml**：百度搜索引擎地图
- **404.html**：自定义 404 错误页面

## 🔗 相关链接

- GitHub：https://github.com/FeynmanNddbb
- 博客：https://blog.midlight.top/
- 链接页面：/link/

## 📧 联系方式

如有问题或建议，欢迎通过以下方式联系：
- 博客评论区留言
- GitHub Issues
- 访问链接页面了解更多联系方式

## 📜 许可证

本项目内容（包括文章、图片等）均为原创，仅供个人学习和参考使用。

---

**最后更新**：2026年2月25日
