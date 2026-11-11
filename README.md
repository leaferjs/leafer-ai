# Leafer AI

LeaferJS 官方 Skills，让 AI 借助官方示例、文档和源码，帮你构建可交互、可编辑的图形应用。

无限画布 · 海报编辑器 · 思维导图 · 分镜画布 · 互动动画 · 小游戏

## 🌱 零基础上手

### 1. 让 AI 帮你安装

打开并登录支持 Skills、能操作文件和执行命令的 AI 编程工具，例如 Codex、Claude Code 或 Cursor。创建一个空文件夹，用该工具打开，然后把下面这段话发给 AI。

```text
请帮我安装 LeaferJS Skill：
npx skills add leaferjs/leafer-ai

请检查环境、配置缺少的依赖，安装到我当前使用的 AI 工具中，并确认安装成功。我没有编程基础，需要我操作时，请一步一步告诉我怎么做。
```

### 2. 描述你想做的作品

安装成功后，在同一文件夹中开启新对话。可以先试试这个需求。

```text
使用 leaferjs，帮我做一个漂亮的旅行照片墙。

初始放入 5 张风景照片，搭配旅行标题和简短文字，采用杂志风排版、柔和背景、圆角与阴影，打开就有完整的示例效果。

我可以拖动、缩放和旋转照片，双击修改文字，也可以缩放和平移画布。提供“添加照片”“适应画布”和“导出 PNG”按钮。

优先使用 LeaferJS 已有的编辑器、文本编辑、视口、视图控制和导出插件。

请帮我完成运行与检查，最后告诉我打开哪个预览、怎样操作。
```

打开 AI 提供的预览，就能体验作品。你也可以把旅行照片墙换成海报编辑器、白板、思维导图或小游戏。

### 3. 继续聊天，完善作品

```text
增加一个“在画布上涂鸦的功能，支持设置笔触大小和颜色，绘制出来的线条支持模拟压感，自动防抖”。
```

遇到问题，把截图或报错发给 AI，让它修复。下次继续时，打开原来的作品文件夹即可。

## 💻 开发者安装

需要 Node.js 22.20 或更新版本。在项目根目录运行，按提示选择目标 AI 工具。

```bash
npx skills add leaferjs/leafer-ai
```

安装后在项目中开启新对话，描述需求即可。

> 使用 leaferjs，检查现有项目结构，加入可缩放、可平移的画布和可编辑文本，沿用现有框架与编码风格。

## 🔄 更新

**交给 AI**，直接发送下面这段话。

```text
请检查 LeaferJS Skill 的安装范围，更新到最新版并确认结果。遇到问题请帮我排查。
```

**自己执行**，按安装范围选择命令。

```bash
npx skills update leaferjs
```

更新后开启新对话使用。Skill 更新提供新的开发指引和知识库，应用的 LeaferJS 依赖版本由项目单独管理。

<details>
<summary>🛠️ 遇到问题？</summary>

- **找不到 node 或 npx**：安装 [Node.js LTS](https://nodejs.org/)，然后重新打开终端；也可以把报错交给 AI 处理。
- **AI 无法执行安装**：切换到支持文件操作和命令执行的模式，或让 AI 指导你手动操作。
- **安装后没有识别**：用 `npx skills list` 查看项目安装，或 `npx skills list -g` 查看全局安装。确认选择了当前使用的 AI 工具，开启新对话并明确说“使用 leaferjs”。
- **安装或更新失败**：将完整报错发给 AI，检查网络、安装范围和 CLI 版本。最新 CLI 可通过 `npx skills@latest` 调用。

更多用法见 [Skills CLI 文档](https://github.com/vercel-labs/skills/blob/main/docs/commands.md)。

</details>

<details>
<summary>📦 仓库维护</summary>

首个 Skill 为 [`leaferjs`](skills/leaferjs/SKILL.md)。

将 [ai-docs](https://github.com/leaferjs/ai-docs) 的内容直接同步到 `skills/leaferjs/`，保留原始 README.md 和目录层级。同步时跳过上游 `.git/`、`skills/`，保留本仓库的 `SKILL.md`。

初始化版本提供 Skill 指引，知识库由维护者同步后随仓库发布。

</details>

## 🔗 相关链接

[LeaferJS 官网](https://www.leaferjs.com/) · [在线示例](https://www.leaferjs.com/examples/) · [Playground](https://www.leaferjs.com/playground/) · [AI 知识库](https://github.com/leaferjs/ai-docs)

[MIT License](LICENSE)
