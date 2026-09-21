---
title: hugo命令集
description: #这是一个副标题
date: 2026-09-21
slug: test-chinese
image: helena-hertz-wWZzXlDpMog-unsplash.jpg
categories:
    - 命令
    - 指令
---
检测环境
---
` Git --version`  ` Git --version`
```
hugo server -D
hugo new site myhugo
Cd myhugo
```
---

```
myblog/
├── archetypes/     ← 文章模板，暂时不用管
├── assets/         ← 自定义样式、脚本放这里（后面会用到）
├── content/        ← 你写的所有文章都放这里
                    ← page左工具
├── layouts/        ← 自定义模板放这里（中级阶段会用到）
├── static/         ← 图片等静态文件放这里
├── themes/         ← 主题放这里，可以放主目录 Stack,assets
                    ← 主题layouts-partials-widget侧边工具
                    ← aplayer+metingjs
└── hugo.toml       ← 站点配置文件，核心配置都在这里
```