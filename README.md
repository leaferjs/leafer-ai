# Leafer AI

LeaferJS 官方 Skills。让 AI 借助官方示例、API 文档和源码，用 [LeaferJS](https://www.leaferjs.com/) 构建可交互、可编辑的图形应用。

## 安装

在项目目录运行，按提示选择你的 AI 编程工具。

```bash
npx skills add leaferjs/leafer-ai
```

需要在多个项目中使用时，可以加 `-g` 安装到用户环境。

## 开始使用

安装后，在 AI 编程工具中描述你想做的功能。你可以直接复制下面的一条提示词。

> 使用 LeaferJS 做一个能在浏览器运行的无限画布，支持缩放、平移和拖拽卡片。先做一个可预览的版本，再告诉我怎么运行。

> 使用 LeaferJS 做一个简易海报编辑器，可以添加文字、拖拽和缩放图形，最后导出 PNG。

> 检查这个项目里 LeaferJS 和插件的版本，帮我找出图形无法选中的原因并修复。

## Skills

| Skill | 用途 |
| --- | --- |
| [`leaferjs`](skills/leaferjs/SKILL.md) | 用 LeaferJS 开发、调试和维护图形应用与插件。适用于无限画布、图形编辑、动画、数据可视化和 2D 游戏。 |

## 仓库结构

```text
leafer-ai/
├── README.md
├── LICENSE
└── skills/
    └── leaferjs/
        ├── SKILL.md
        ├── README.md
        ├── introduction.md
        ├── feature.md
        ├── performance.md
        ├── examples/
        ├── guide/
        ├── reference/
        ├── plugin/
        ├── src/
        └── update/
```

`skills/leaferjs/SKILL.md` 是 AI 的使用指引。同目录的 README 和知识库内容来自 [leaferjs/ai-docs](https://github.com/leaferjs/ai-docs)，由维护者本地同步。

将 ai-docs 仓库内容直接同步到 `skills/leaferjs/`，保留原始目录层级及 README.md。同步时排除上游 `.git/` 和 `skills/`，并保留本仓库的 `skills/leaferjs/SKILL.md`。初始化版本仅包含 Skill 指引，以上知识库文件和目录会在同步后出现。

提交同步后的内容即可随 Skill 一起分发。

## 相关链接

[LeaferJS 官网](https://www.leaferjs.com/) · [在线示例](https://www.leaferjs.com/examples/) · [Playground](https://www.leaferjs.com/playground/) · [AI 知识库](https://github.com/leaferjs/ai-docs)

## License

[MIT](LICENSE)
