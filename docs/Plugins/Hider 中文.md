---
permalink: plugins/hider
---

#plugins

[在 Obsidian 中打开插件](obsidian://show-plugin?id=obsidian-hider)

## 概述

此插件允许你隐藏 Obsidian UI 的部分内容。它可以帮助你创建无干扰界面，并配置 Obsidian 以获得更 [[macOS 配置|原生 macOS 外观]]。

- 隐藏应用功能区（可绑定快捷键）
- 隐藏状态栏（可绑定快捷键）
- 隐藏仓库名称
- 隐藏窗口边框
- 隐藏滚动条
- 隐藏工具提示
- 隐藏搜索建议
- 隐藏阅读视图中的元数据块

## 开发者

Hider 在功能开启时会在 `body` 元素上注入以下类。这些类与 [[CSS 代码片段]] 结合使用时很有用。

| 开关       | 类名                        |
| ---------- | --------------------------- |
| 标题栏     | `.hider-frameless`          |
| 应用功能区 | `.hider-ribbon`             |
| 仓库名称   | `.hider-vault`              |
| 状态栏     | `.hider-status`             |
| 滚动条     | `.hider-scroll`             |
| 搜索建议   | `.hider-search-suggestions` |
| 工具提示   | `.hider-tooltips`           |
| 说明       | `.hider-instructions`       |
| 元数据     | `.hider-meta`               |
