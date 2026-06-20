![](/cover.png)

详细文档请访问 [minimal.guide](https://minimal.guide)

Minimal 是一款适用于桌面、移动端和平板设备的 [Obsidian](https://obsidian.md/) 主题。通过配套插件 [Minimal Theme Settings](https://community.obsidian.md/plugins/obsidian-minimal-settings) 和 [Hider](https://community.obsidian.md/plugins/obsidian-hider) 自定义颜色、字体等。Obsidian 官方 [最佳主题奖](https://forum.obsidian.md/t/best-of-2020-awards-results/11217) 得主 ✨

## 关于 Minimal

- [截图](#截图)
- [安装](#安装)
- [配套插件](#配套插件)
- [设置](#设置)
- [配色方案](#配色方案)
- [插件支持](#插件支持)
- [辅助类](#辅助滤镜和类)
- [替代复选框](#替代复选框)
- [快捷键](#快捷键)
- [贡献](#贡献)
- [开发者](#开发者)
- [许可证](#许可证)
- [免责声明](#免责声明)

## 截图

**背景样式** 包括低对比度、高对比度以及适合 OLED 设备的纯黑选项

![](/docs/Images/minimal-variants.png)

用于表格和卡片布局的 **辅助类** 允许你创建强大的工作流

![](/docs/Images/minimal-movies.png)

将 **专注模式** 与 **图片网格** 和 **图片宽度** 选项结合使用，让你沉浸在视觉项目中

![](/docs/Images/minimal-img-grid.png)

Minimal 包含对数十个热门插件的支持，如 **Calendar**、**Kanban**、**Dataview**、**Outliner**、**Excalidraw** [等](#插件支持)

![](/docs/Images/minimal-plugins.png)

## 安装

安装主题

- 打开 Obsidian 设置
- 进入 `外观` 并点击 `管理`
- 在社区主题中搜索"Minimal"并点击 `使用`

安装配套插件

- 进入 `社区插件` 并关闭 `受限模式`
- 在社区插件中搜索"Minimal Theme Settings"并点击 `安装`，然后 `启用`

有问题？加入官方 [Obsidian Discord](https://discord.gg/veuWUTm) 上的 [Minimal 频道](https://discord.com/channels/686053708261228577/931008597557649410)。

## 配套插件

- [Minimal Theme Settings 插件](https://github.com/kepano/obsidian-minimal-settings) 允许你自定义配色方案、字体、[快捷键](#快捷键)，并访问主要功能开关。此插件强烈推荐给所有 Minimal 用户。
- [Hider 插件](https://github.com/kepano/obsidian-hider) 推荐用于隐藏 Obsidian UI 元素，如窗口边框、滚动条、工具提示等。使用 Hider 关闭主工具栏（即应用功能区）时，可以通过悬停在窗口左下边缘来访问。
- [Style Settings 插件](https://github.com/mgmeyers/obsidian-style-settings) 允许你创建自定义配色方案。此插件为可选。

## 设置

以下设置可以通过 [Minimal Theme Settings](https://github.com/kepano/obsidian-minimal-settings) 插件访问。以下许多设置可以通过[快捷键](#快捷键)切换。

### 界面颜色和字体

- [背景对比度](https://minimal.guide/Features/Background+contrast) — 包括适合 OLED 设备的纯黑深色模式
- [配色方案](https://minimal.guide/Features/Color+schemes) — 包括 Catppuccin、Dracula、Everforest、Gruvbox、macOS、Nord、Solarized [等](#配色方案)
- [行宽](https://minimal.guide/Features/Line+width) — 设置面板内的正常行宽和最大宽度

你也可以使用 Style Settings 插件进行更深层次的自定义

### 功能

- [主要导航的文字标签](https://minimal.guide/Features/Text+labels+for+primary+navigation) — 为左上角导航添加文字标签，注意英语以外的语言需要翻译代码片段 [更多本地化信息](#本地化)
- [专注模式](https://minimal.guide/Features/Focus+mode) — 隐藏标题栏和状态栏
- [彩色边框](https://minimal.guide/Features/Colorful+frame) — 使用强调色作为应用窗口顶部区域
- [彩色标题](https://minimal.guide/Features/Colorful+headings) — 每种标题使用不同颜色
- 隐藏工作区边框 — 移除分割线以获得更简洁的外观
- 裁剪文件名 — 文件名裁剪为一行

### 布局选项

控制图片、表格和内嵌框架。这些设置也可以使用[辅助类](#辅助滤镜和类)在逐文件基础上启用。

- [图片网格](https://minimal.guide/Block+types/Image+grids) — 将连续图片转换为列。要创建新行，在图片之间添加额外的空行。
- [块宽度](https://minimal.guide/Features/Block+width) — 按类型控制元素的宽度。

## 配色方案

### 预设配色方案

Minimal 提供的配色方案可以使用 [Minimal Theme Settings](https://github.com/kepano/obsidian-minimal-settings) 插件分别为浅色和深色模式选择。配色方案包括 Dracula、Everforest、Gruvbox、macOS、Nord、Notion、Solarized 和 Things。

![Minimal Theme Settings](/docs/Images/minimal-color-schemes.gif)

### 自定义配色方案

你可以使用 Style Settings 插件自定义你的配色方案。为了更方便地查看更改，可以使用命令面板（默认 `CMD + P`）在新面板中打开 Style Settings。使用 Style Settings 你可以自定义 Minimal 的颜色、字体大小、字体样式以及更多细节。

![Style Settings](/docs/Images/minimal-style-settings.gif)

## 插件支持

大多数插件与 Minimal 配合良好，但以下插件获得了特别的优化和支持：

- [Calendar](https://github.com/liamcain/obsidian-calendar-plugin)
- [Charts](https://github.com/phibr0/obsidian-charts)
- [Checklist](https://github.com/delashum/obsidian-checklist-plugin)
- [Dataview](https://github.com/blacksmithgu/obsidian-dataview)
- [Dictionary](https://github.com/phibr0/obsidian-dictionary)
- [Excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin)
- [Git](https://github.com/denolehov/obsidian-git)
- [Hider](https://github.com/kepano/obsidian-hider)
- [Kanban](https://github.com/mgmeyers/obsidian-kanban)
- [Outliner](https://github.com/vslinko/obsidian-outliner)
- [QuickAdd](https://github.com/chhoumann/quickadd)

## 辅助滤镜和类

## 图片滤镜

可以添加图片滤镜来创建以下效果。在图片链接末尾添加滤镜名称使用，例如 `![[image.jpeg#invert]]`

| 滤镜       | 说明                                                    |
| ---------- | ------------------------------------------------------- |
| `#invert`  | 在深色模式下反转图片 — 适用于浅色背景上的图表和手写内容 |
| `#invertW` | 在浅色模式下反转图片 — 适用于深色背景上的图表和手写内容 |
| `#circle`  | 将图片裁剪为圆形                                        |
| `#outline` | 在图片周围添加轮廓                                      |

## CSS 辅助类

CSS 辅助类可以使用 `cssClasses` [YAML front matter 键](https://help.obsidian.md/Advanced+topics/YAML+front+matter)在逐文件基础上添加。这些类可以组合使用，因此你可以包含多个类来组合效果。

例如，在文件顶部使用以下代码来启用卡片布局：

```
---
cssClasses: cards
---
```

### 图片网格

将连续图片转换为列。要创建新行，在图片之间添加额外的空行。[了解更多。](https://minimal.guide/Block+types/Image+grids)

| 类名       | 说明         |
| ---------- | ------------ |
| `img-grid` | 激活图片网格 |

### 表格、图片和内嵌框架的行宽控制

按类型控制元素的宽度。[了解更多。](https://github.com/kepano/obsidian-minimal/releases/tag/4.2.0)

| 类名                                    | 说明                     |
| --------------------------------------- | ------------------------ |
| `table-100`, `img-100`, `iframe-100`    | 填充面板宽度的 100%      |
| `table-max`, `img-max`, `iframe-max`    | 填充最大行宽（默认 88%） |
| `table-wide`, `img-wide`, `iframe-wide` | 填充宽行宽               |

### 卡片

使用 `cards` 将 Dataview 表格转换为卡片。兼容表格宽度类。注意 `cards` 必须存在，其他类才能生效。[了解更多。](https://minimal.guide/Block+types/Cards)

| 类名                  | 说明                                    |
| --------------------- | --------------------------------------- |
| `cards`（必需）       | 将所有 Dataview 表格设置为卡片布局      |
| `cards-align-bottom`  | 将卡片的最后一个元素对齐到底部          |
| `cards-cover`         | 图片调整大小以填充定义的空间            |
| `cards-16-9`          | 将卡片中的图片适配为 16:9 比例          |
| `cards-1-1`           | 将卡片中的图片适配为 1:1 比例（正方形） |
| `cards-2-1`           | 将卡片中的图片适配为 2:1 比例           |
| `cards-2-3`           | 将卡片中的图片适配为 2:3 比例           |
| `cards-cols-1` 到 `8` | 强制指定列数（从 1 到 8）               |

### 表格和 Dataview

控制表格的行和列样式。[了解更多。](https://github.com/kepano/obsidian-minimal/releases/tag/4.1.7)

| 类名            | 说明                         |
| --------------- | ---------------------------- |
| `table-nowrap`  | 禁用表格单元格中的自动换行   |
| `table-wrap`    | 强制表格单元格换行           |
| `table-numbers` | 为表格添加行号               |
| `table-tabular` | 在表格中使用等宽数字         |
| `table-small`   | 在表格中使用小字体           |
| `table-tiny`    | 在表格中使用极小字体         |
| `table-lines`   | 在所有表格单元格周围添加边框 |
| `row-lines`     | 在表格行之间添加边框         |
| `col-lines`     | 在表格列之间添加边框         |
| `row-alt`       | 为交替表格行添加斑马纹背景   |
| `col-alt`       | 为交替表格列添加斑马纹背景   |

### 嵌入和内容包含

| 类名           | 说明                         |
| -------------- | ---------------------------- |
| `embed-strict` | 内容包含无缝地出现在文本流中 |

## 替代复选框

Minimal 支持多种复选框样式。这些允许你标记未完成、已取消、已重新安排等任务。[查看截图和详情](https://minimal.guide/Block+types/Checklists)

| 语法    | 说明   |
| ------- | ------ |
| `- [ ]` | 待办   |
| `- [/]` | 未完成 |
| `- [x]` | 已完成 |
| `- [-]` | 已取消 |
| `- [>]` | 已转发 |
| `- [<]` | 已排期 |
| `- [?]` | 问题   |
| `- [!]` | 重要   |
| `- [*]` | 星标   |
| `- ["]` | 引用   |
| `- [l]` | 位置   |
| `- [b]` | 书签   |
| `- [i]` | 信息   |
| `- [S]` | 储蓄   |
| `- [I]` | 想法   |
| `- [p]` | 优点   |
| `- [c]` | 缺点   |
| `- [f]` | 火焰   |
| `- [k]` | 关键   |
| `- [w]` | 胜利   |
| `- [u]` | 向上   |
| `- [d]` | 向下   |

## 快捷键

快捷键仅在使用 Minimal Theme Settings 插件时可用。

### 背景和边框

- 在浅色和深色模式之间切换
- 在浅色模式样式之间循环切换
- 在深色模式样式之间循环切换
- 切换侧边栏边框

### 布局控制

- 切换图片网格
- 在图片宽度选项之间循环切换
- 在表格宽度选项之间循环切换
- 在内嵌框架宽度选项之间循环切换

### 其他

- 切换专注模式
- 切换彩色标题
- 增大和减小正文字体大小

## 贡献

如果你想添加插件支持，或发现了想要帮助修复的 Bug，请不要犹豫，提交 Pull Request。有问题？加入官方 [Obsidian Discord](https://discord.gg/veuWUTm) 上的 [Minimal 频道](https://discord.com/channels/686053708261228577/931008597557649410)。

### 插件支持

插件作者和开发者可以通过提交 Pull Request 来添加 Minimal 主题的支持。参见 [src/scss/plugins](https://github.com/kepano/obsidian-minimal/tree/master/src/scss/plugins) 文件夹中当前支持的插件代码片段示例。

## 开发者

### 构建说明

**设置**

```
npm install
```

**定义本地路径**

要直接构建到你的 Obsidian 仓库中，将 `.env.example` 重命名为 `.env` 并将 `OBSIDIAN_PATH` 更新为你的 Obsidian 主题文件夹的本地路径。

**运行**

```
npm run dev    # 监视更改并重新构建
npm run build  # 一次性构建
```

这会构建两个文件：`theme.css`，压缩的分发文件（用于社区主题商店），也会复制到你的仓库以实现实时重载；以及 `Minimal.css`，未压缩的副本保存在项目根目录中。

## 许可证

### Minimal for 桌面和移动版

Minimal for Obsidian 应用根据 MIT 许可证授权，允许你修改和重新分发代码，但你必须在 CSS 文件中保留版权和许可声明。这包括你可能提取为独立代码片段的任何代码。

**如果你想分发 Minimal 的分支或其部分代码，请保留我的 [Buy me a coffee](https://www.buymeacoffee.com/kepano) 链接在你的 Readme 中。**

Minimal 频繁更新以保持与最新版本 Obsidian 的同步。为了方便与最新改进保持同步，我建议使用 [GitHub 的 fork 功能](https://docs.github.com/en/get-started/quickstart/fork-a-repo)，这样你可以将最新的更改合并到你的分支中。如果你有任何问题，不要犹豫，在 Obsidian Discord 群组中联系我。

### Minimal for Obsidian Publish

Minimal for Obsidian Publish 是 Minimal 的一个独立版本，遵循相同的设计原则但针对 Web 进行了优化。它同样根据 MIT 许可证授权，可在 [minimal.guide](https://minimal.guide/publish/download) 或 [obsidian-minimal-publish](https://github.com/kepano/obsidian-minimal-publish) 仓库获取。

## 免责声明

本主题按原样提供，专为我在 macOS 上个人使用 Obsidian 而设计。因此，它未在所有操作系统和使用场景下进行彻底测试。

本主题修改了 Obsidian 界面的重要部分，因此可能会在未来的更新中出现兼容性问题。它也可能与你拥有的其他自定义 CSS 不兼容。
