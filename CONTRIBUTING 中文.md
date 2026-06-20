# 贡献到 Minimal

Minimal 已被视为功能完备。未来的主要目标是保持与新的 Obsidian 版本同步，因此最有用的贡献是 Bug 修复和新 Obsidian 版本的兼容性补丁。新功能不太可能被合并。

## 报告问题

在提交问题之前，请搜索[现有问题](https://github.com/kepano/obsidian-minimal/issues)以避免重复。报告 Bug 时，请包含：

- Obsidian 版本和操作系统
- Minimal 版本
- 复现步骤，以及相关截图
- 是否在其他主题禁用时出现该问题

## 提交 Pull Request

1. Fork 仓库并从 `master` 创建分支。
2. 在 `src/scss` 中进行更改。切勿直接编辑 `obsidian.css` 或 `Minimal.css`，因为它们是生成的文件。
3. 在本地构建并在 Obsidian 中测试（参见[构建说明](README.md#build-instructions)）。
4. 提交 Pull Request，简要描述更改了什么以及为什么。

保持 PR 聚焦。每个 PR 一个修复或功能使审查更容易。

## 添加插件支持

插件样式位于 [`src/scss/plugins`](src/scss/plugins)。使用现有文件作为模板，并尽量遵循 Minimal 的颜色变量和间距约定，使插件感觉自然。

## 改进文档

[minimal.guide](https://minimal.guide) 上的文档站点从本仓库的 [`docs`](docs) 文件夹发布。如果你发现有过时、缺失或不清楚的内容，欢迎编辑和补充。只需针对 `docs` 中的相关文件提交 PR。

## 问题

加入官方 [Obsidian Discord](https://discord.gg/veuWUTm) 上的 [Minimal 频道](https://discord.com/channels/686053708261228577/931008597557649410)。
