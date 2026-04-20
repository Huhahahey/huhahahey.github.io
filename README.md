# 中文技术博客

基于 Hugo Winston Theme 构建的现代化中文技术博客。

## 📝 博客内容

本博客专注于分享技术经验和最佳实践,涵盖以下领域:

- **前端开发**: Vue.js、React、TypeScript 等现代前端技术
- **后端开发**: Node.js、Python、Go 等服务端技术
- **DevOps**: Docker、Kubernetes、CI/CD 等部署和运维实践
- **系统架构**: 微服务、设计模式、性能优化等架构设计

## 🚀 快速开始

### 前置要求

- [Hugo](https://gohugo.io/) (推荐 v0.55.0 或更高版本)
- Git

### 本地运行

```bash
# 克隆项目
git clone <repository-url>
cd mynewsite

# 启动开发服务器
hugo server -D

# 访问 http://localhost:1313/
```

### 构建生产版本

```bash
# 生成静态文件
hugo

# 生成的文件位于 public/ 目录
```

## 📂 项目结构

```
mynewsite/
├── content/              # 博客内容
│   ├── posts/           # 技术文章
│   └── pages/           # 静态页面(如关于页)
├── data/                # 数据文件
│   ├── author.json      # 作者信息
│   └── social.json      # 社交媒体链接
├── themes/              # 主题文件
├── config.toml          # 站点配置
└── README.md            # 说明文档
```

## ✏️ 创建新文章

使用 Hugo 命令行工具创建新文章:

```bash
# 创建新的博客文章
hugo new posts/my-new-post.md

# 创建新的页面
hugo new pages/my-page.md
```

文章模板包含以下 Front Matter:

```yaml
---
title: 文章标题
date: 2024-01-01
description: "文章描述"
image: images/cover.jpeg
tags:
   - 标签1
   - 标签2
---

文章内容...
```

## 🎨 自定义配置

### 修改站点信息

编辑 `config.toml`:

```toml
baseURL = "/"
languageCode = "zh-cn"
title = "你的博客标题"

[params]
  twitter_handle = "@yourhandle"
  showAuthorOnHomepage = true
  # ... 其他配置
```

### 更新作者信息

编辑 `data/author.json`:

```json
{
  "name": "你的名字",
  "title": "你的职位",
  "image": "images/author.png"
}
```

### 添加社交媒体链接

编辑 `data/social.json`:

```json
{
  "links": [
    {
      "name": "github",
      "url": "https://github.com/yourusername",
      "image": "images/social/github.svg"
    }
  ]
}
```

## 📱 响应式设计

本主题完全响应式,在以下设备上都能完美显示:

- 📱 手机
- 📱 平板
- 💻 笔记本
- 🖥️ 桌面电脑

## 🎯 SEO 优化

- 语义化 HTML 结构
- 优化的 Meta 标签
- 支持 Google Analytics
- 自动生成 Sitemap
- RSS Feed 支持

## 🔧 技术栈

- **静态站点生成器**: [Hugo](https://gohugo.io/)
- **主题**: [Hugo Winston Theme](https://github.com/zerostaticthemes/hugo-winston-theme)
- **样式**: SCSS
- **字体**: Noto Sans SC (思源黑体)
- **代码高亮**: Pygments

## 📄 许可证

本项目采用 MIT 许可证。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request!

## 📮 联系方式

- GitHub: [你的主页](https://github.com)
- Twitter: [@techblog](https://twitter.com)
- LinkedIn: [个人资料](https://www.linkedin.com)

---

Made with ❤️ using Hugo