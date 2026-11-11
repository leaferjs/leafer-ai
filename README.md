# Leafer AI

LeaferJS 官方 Skills。让 AI 借助官方示例、API 文档和源码，用 [LeaferJS](https://www.leaferjs.com/) 构建可交互、可编辑的图形应用。

描述你的想法，让 AI 帮你制作无限画布、海报编辑器、流程图、互动动画或小游戏。

## 快速安装

已经配置好 AI 编程工具和 Node.js？在项目目录运行以下命令，按提示选择使用的工具。

```bash
npx skills add leaferjs/leafer-ai
```

首次接触这些工具，可以按照下面的步骤操作。

## 零基础快速上手

你只需要描述想做什么，AI 会借助 LeaferJS 的官方资料，帮你创建、运行和修改作品。

### 1. 打开 AI 编程工具

在电脑上打开并登录支持 Skills、能创建文件和执行命令的 AI 编程工具，例如 Codex、Claude Code 或 Cursor。

创建一个空文件夹，例如 `my-leafer-app`，在工具中打开它，用来存放你的第一个作品。如果你找不到入口，可以把这句话发给 AI。

```text
我想用 LeaferJS 做第一个作品，请指导我创建并打开一个作品文件夹。请根据我正在使用的工具，一步一步告诉我在哪里点击。
```

### 2. 把安装交给 AI

将下面整段文字复制到 AI 的聊天输入框并发送。

```text
请帮我安装 LeaferJS Skill，方便我以后用自然语言制作图形应用。

安装命令：
npx skills add leaferjs/leafer-ai -g

请先检查运行环境，如果缺少 Node.js 等依赖，请帮我配置。把 Skill 安装到我当前使用的 AI 编程工具中，完成后检查 leaferjs 是否安装成功。

我没有编程基础，请直接帮我完成你能执行的操作。遇到需要我下载安装软件、登录或授权的步骤，请告诉我具体在哪里操作、选择什么。
```

按 AI 的提示完成必要操作。安装成功后，在同一个作品文件夹中开启新对话，开始制作。

### 3. 说出你想做的作品

第一次可以直接复制这个简单的白板需求。

```text
请使用 leaferjs Skill，帮我做一个简单好看的白板。

先放三张不同颜色的卡片，每张卡片上写一段文字。我可以拖动卡片，也可以缩放和平移整个白板。

我没有编程基础，请帮我完成代码、环境配置和运行，检查主要功能是否正常。完成后告诉我打开哪个预览，以及怎样拖动、缩放和平移。
```

等 AI 提供预览入口后，打开作品并试着拖动卡片。还可以把需求换成你自己的想法。

| 想做的作品 | 可以直接发给 AI 的话 |
| --- | --- |
| 海报编辑器 | 使用 leaferjs Skill，做一个可以添加文字和图片、调整位置和大小、导出 PNG 的海报编辑器。 |
| 思维导图 | 使用 leaferjs Skill，做一个简单的思维导图工具，可以添加节点、连接节点、拖动和缩放。 |
| 分镜画布 | 使用 leaferjs Skill，做一个分镜画布，可以放入图片、填写分镜说明，并调整排列顺序。 |
| 互动小游戏 | 使用 leaferjs Skill，做一个点击目标得分的小游戏，显示分数和倒计时，并帮我运行预览。 |

### 4. 像聊天一样修改

在同一个对话里继续说出你的想法。

> 把卡片改成圆角，再增加一个“添加卡片”的按钮。

> 文字放大一点，背景换成浅灰色。

> 增加“导出图片”按钮，让我能把作品保存下来。

如果画面或功能不符合预期，把截图、报错或具体操作过程发给 AI。

```text
我刚才拖动卡片时遇到了这个问题，请帮我找出原因并修复，再重新运行预览，告诉我怎么确认已经修好。
```

下次继续制作时，打开原来的作品文件夹，让 AI 先查看已有内容，再继续修改。

### 5. 让 AI 帮你更新 Skill

想获取新的指引和知识库时，把下面这段话发给 AI。

```text
请帮我更新全局安装的 LeaferJS Skill：

npx skills update leaferjs -g

请执行更新并检查结果。如果遇到问题，请帮我排查，并告诉我需要做什么。
```

更新完成后开启新对话，就可以继续使用。

如果 AI 提示当前模式只能聊天，请切换到该工具支持文件操作和命令执行的模式，或让它一步一步指导你手动安装。手动安装与更新命令见下方。

## 有编程背景的用户

### 安装到当前项目

在项目根目录执行，按提示选择目标 Agent。

```bash
npx skills add leaferjs/leafer-ai
```

也可以指定 Codex。

```bash
npx skills add leaferjs/leafer-ai -a codex
```

在多个项目中使用时，添加 `-g`。

```bash
npx skills add leaferjs/leafer-ai -a codex -g
```

其他常用 Agent 参数包括 `claude-code` 和 `cursor`。Skill 安装目录由 CLI 根据目标工具和安装范围处理。

### 确认安装并使用

查看当前项目已安装的 Skills。

```bash
npx skills list
```

在该项目中开启新对话，明确调用 Skill 并提供目标。

> 使用 leaferjs Skill，先检查现有依赖与目录结构，在当前项目中加入可缩放、可平移的画布和可编辑文本，沿用项目现有框架与编码风格。

> 使用 leaferjs Skill，检查这个图形无法选中的原因，参考对应版本的官方示例修复，并验证交互。

## 更新 Skill

更新可以获得维护者发布的新指引、示例和知识库内容。打开终端，按自己的安装范围选择命令。

| 安装方式 | 操作位置 | 更新 LeaferJS |
| --- | --- | --- |
| 全局安装，安装时使用了 `-g` | 任意目录 | `npx skills update leaferjs -g` |
| 当前项目安装 | 该项目根目录 | `npx skills update leaferjs -p` |

希望先检查更新，可以运行以下命令。检查项目安装时，在项目根目录执行。

```bash
npx skills check
```

更新所有已安装的 Skills，可以运行以下命令并按提示选择范围。

```bash
npx skills update
```

更新完成后，在 AI 工具中开启新对话使用更新后的 Skill。已有应用的 LeaferJS npm 依赖版本由项目单独管理。

## 常见问题

### 提示找不到 node 或 npx

确认已经安装 Node.js，然后重新打开终端。如果仍然无法运行，将报错内容交给 AI 编程工具，检查 Node.js 的安装和环境变量。

### 安装时无法连接 GitHub 或 npm

确认网络可以访问 GitHub 和 npm，然后重新运行安装命令。如果仍然失败，保留完整报错交给 AI 排查。

### 安装成功，但 AI 没有使用 Skill

先根据安装范围运行 `npx skills list` 或 `npx skills list -g`，确认列表中有 `leaferjs`。检查安装时选择的 Agent 与当前使用的工具是否一致，再开启新对话并明确说“请使用 leaferjs Skill”。

### 更新时找不到 leaferjs

确认使用了正确的安装范围。项目安装需要进入原项目目录。如果文件是手动复制的，可以重新运行本 README 的安装命令，让 CLI 记录来源后再管理更新。

### 命令提示不支持 update 参数

使用最新版本的 CLI 重试，例如更新全局安装的 LeaferJS。

```bash
npx skills@latest update leaferjs -g
```

更多命令与兼容信息可查阅 [Skills CLI 官方文档](https://github.com/vercel-labs/skills/blob/main/docs/commands.md)。

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
