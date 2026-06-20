---
cssclasses:
    - img-grid
    - img-zoom
permalink: guides/image-gallery
description: 使用 Minimal for Obsidian Publish 创建图片画廊。图片可以并排放置，点击可打开放大版本。
---

#guides

## 概述

此画廊使用 [[图片网格]] 和 [[Minimal for Obsidian Publish 中文]]。图片可以并排放置，点击可打开放大版本。

![[eink-mode1.jpg]]
![[eink-mode2.jpg]]

## 前提条件

本指南需要你有一个 [Obsidian Publish](https://obsidian.md/publish) 站点并配置了[自定义域名](https://help.obsidian.md/Obsidian+Publish/Set+up+a+custom+domain)，这是在 Obsidian Publish 上使用 `publish.js` 所必需的。

## 第 1 步：将主题和 JS 代码添加到你的仓库

1. 下载 [[Minimal for Obsidian Publish 中文]] 1.1+ 版本，并将其添加到你的仓库。
2. 下载包含图片缩放代码的 [publish.js](https://github.com/kepano/obsidian-minimal-publish/blob/master/publish.js)，并将其添加到你的仓库。

了解更多关于如何在官方 [Obsidian 帮助站点](https://help.obsidian.md/Obsidian+Publish/Customize+your+site)上使用 `publish.css` 和 `publish.js` 的信息。

## 第 2 步：为你的笔记添加辅助类

对于需要启用缩放的笔记，在 `cssclasses` 中包含 `img-zoom` [[辅助类|辅助类]]。如果你还想启用 [[图片网格]]，也可以包含 `img-grid` 类。

```
---
cssclasses:
  - img-grid
  - img-zoom
---
```

从这里你可以按照 [[图片网格]] 中的说明向笔记添加图片。请注意，图片缩放的代码目前仅支持本地图片嵌入（不支持远程资源）。

## 第 3 步：发布你的笔记和资源

最后一步是发布所有相关资源：

- 你的 `publish.js` 文件
- 你的 `publish.css` 文件
- 你的笔记和图片

更多信息可在 [Obsidian 帮助站点](https://help.obsidian.md/Obsidian+Publish/Publish+and+unpublish+notes)找到。

完成！刷新你的站点即可看到图片画廊。请注意，可能需要硬刷新（使用 `CMD + Shift + R`）或等待几分钟以清除缓存。

## 将此代码适配到其他 Publish 主题

与此功能相关的资源可以在 Minimal for Publish 的 [GitHub 仓库](https://github.com/kepano/obsidian-minimal-publish/tree/master)中找到。你可以使用它来将 CSS 和 JS 适配到其他 Publish 主题。
