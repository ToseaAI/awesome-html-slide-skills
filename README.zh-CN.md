<h1 align="center">Awesome HTML Slide Skills</h1>

<p align="center"><i>面向 Claude Code、Codex、Cursor、OpenClaw、Hermes 的 HTML 演示文稿 Skill 与模板库精选——一句话生成单文件 HTML 演示文稿的开源生态全景。</i></p>

<p align="center">
  <a href="LICENSE"><img alt="License: CC BY 4.0" src="https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg"></a>
  <a href="https://tosea.ai/slide-skills"><img alt="Live on Tosea.ai" src="https://img.shields.io/badge/Live%20on-Tosea.ai-000000?style=flat&logo=safari&logoColor=white"></a>
  <a href="https://tosea.ai"><img alt="Made by Tosea.ai" src="https://img.shields.io/badge/Made%20by-Tosea.ai-000000?style=flat"></a>
  <a href="https://github.com/ToseaAI/awesome-html-slide-skills/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/ToseaAI/awesome-html-slide-skills?style=flat&color=yellow"></a>
  <a href="https://github.com/ToseaAI/awesome-html-slide-skills/network/members"><img alt="GitHub forks" src="https://img.shields.io/github/forks/ToseaAI/awesome-html-slide-skills?style=flat&color=blue"></a>
  <a href="https://awesome.re"><img alt="Awesome" src="https://awesome.re/badge-flat2.svg"></a>
</p>

<p align="center"><a href="README.md">English</a> · <b>中文</b></p>

一份精心整理的开源清单，收录 **HTML 演示文稿生成 Skill**——可被 AI 编程 Agent（Claude Code / Codex / Hermes / OpenClaw / Cursor）加载的打包技能，以及配套的 HTML 模板库。一句话、一份大纲、一篇 Markdown，即可生成零依赖、单文件 HTML 演示文稿。

本仓库收录的全部是真实可访问的 GitHub 仓库。星标数通过 GitHub API 实时获取，并作为排序的唯一依据。简介、亮点与预览图来自项目自身 README，版权归原作者所有。

> **在线浏览 → [tosea.ai/slide-skills](https://tosea.ai/slide-skills)。** 同一份精选，渲染成更易扫读的网页画廊，附带实时 GitHub 统计。README 是 source of truth，网页镜像它。

> **由 [Tosea.ai](https://tosea.ai) 维护** —— 我们专注于 AI 原生的演示文稿工具链。如果你开源了一个 HTML Slide Skill 或模板库，欢迎 [提交 PR](CONTRIBUTING.md)。

---

## 精选效果展示

下面每张图都是对应项目自己的 demo，点击即可跳转到该条目。

<table align="center"><tr>
<td align="center" width="25%"><a href="#2-alchaincyfhuashu-design--19547"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c2-slides-pptx-en.gif" width="220" alt="huashu-design — slides + PPTX export"/></a><br><sub><b>huashu-design</b><br>19.5k ⭐</sub></td>
<td align="center" width="25%"><a href="#4-nicobailonvisual-explainer--8837"><img src="https://raw.githubusercontent.com/nicobailon/visual-explainer/main/banner.png" width="220" alt="visual-explainer banner"/></a><br><sub><b>visual-explainer</b><br>8.8k ⭐</sub></td>
<td align="center" width="25%"><a href="#5-lewisluluhtml-ppt-skill--6411"><img src="https://raw.githubusercontent.com/lewislulu/html-ppt-skill/main/docs/readme/hero.gif" width="220" alt="html-ppt-skill hero"/></a><br><sub><b>html-ppt-skill</b><br>6.4k ⭐</sub></td>
<td align="center" width="25%"><a href="#6-1weihoopen-slide--5498"><img src="https://github.com/user-attachments/assets/02f5e6d7-12a7-4a8e-88e7-ae8770a96584" width="220" alt="open-slide cover"/></a><br><sub><b>open-slide</b><br>5.5k ⭐</sub></td>
</tr><tr>
<td align="center" width="25%"><a href="#9-archlizhengfrontend-slides-editable--362"><img src="https://raw.githubusercontent.com/archlizheng/frontend-slides-editable/main/docs/preset-previews/bold-signal-cover.png" width="220" alt="bold-signal cover preset"/></a><br><sub><b>frontend-slides-editable</b><br>362 ⭐</sub></td>
<td align="center" width="25%"><a href="#11-likakumck-ppt-design-skill--198"><img src="https://github.com/user-attachments/assets/075ec46d-dd73-4454-92d0-84184b78d276" width="220" alt="Mck-ppt-design cover slide"/></a><br><sub><b>Mck-ppt-design-skill</b><br>198 ⭐</sub></td>
<td align="center" width="25%"><a href="#t1-zarazhangruibeautiful-html-templates--3096"><img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/soft-editorial-4.png" width="220" alt="soft editorial template"/></a><br><sub><b>beautiful-html-templates</b><br>3.1k ⭐</sub></td>
</tr></table>

---

## 目录

- [关于这个清单](#关于这个清单)
- [Skills](#skills)
  - [Tier S · 基础设施级 / 1k+ stars](#tier-s--基础设施级--1k-stars)
  - [Tier A · 生产可用 / 100–1000 stars](#tier-a--生产可用--1001000-stars)
  - [Tier B · 新兴 / 专精方向](#tier-b--新兴--专精方向)
- [Templates](#templates)
- [贡献指南](#贡献指南)
- [License](#license)

---

## 关于这个清单

**什么算「HTML Slide Skill」？**

Skill 是一个自包含的能力包——通常由一份 `SKILL.md`、若干风格参考文件、以及少量运行时代码组成——AI 编程 Agent 可以加载它，然后产出完整的 HTML 演示文稿。本清单中绝大多数项目针对 Claude Code 的 [Agent Skills](https://docs.claude.com/en/docs/claude-code/skills) 规范设计，但也有不少是 Agent 无关的，可在 Codex、Cursor、OpenClaw、Hermes 等任何能读取 Markdown 指令的 Agent 上运行。

**Skill vs. Template：**

- **Skills**（本清单的核心）是「生成式」的：Agent 会根据你的 prompt、大纲或文档智能选择版式与主题。包含规划逻辑、内容路由、Anti-AI-Slop 检查、完整设计系统。
- **Templates** 是「静态」的：手工打磨的 HTML/CSS 骨架，等你（或 Agent）来填充。规模更小，但作为 Skill 引用的视觉基准非常重要。

**为什么需要这个清单：**

HTML 演示文稿正悄悄成为 AI 生成场景下的首选格式——可在任何浏览器中渲染、可嵌入任意内容、可被版本控制干净地管理、永远不会因为 PowerPoint 找不到字体而在路演现场翻车。整个生态在 2026 年初彻底爆发，两个月内我们就数到了 20+ 个认真的 Skill 包，但一直没有人把它们汇总到一处。这里就是那个汇总。

---

## Skills

> 按 GitHub 星标数降序排列。星标数据更新于 2026-06-23。
> Tier 的划分是经验性的，并非价值判断——一个 24 颗星的华为风 Skill，在做战略汇报这个场景下，几乎一定比 17k 星的通用方案更合适。

### Tier S · 基础设施级 / 1k+ stars

这一档是大多数其他项目引用、fork 或对标的对象。如果你是第一次接触 HTML Slide Skill，从这里开始。

---

#### 1. [zarazhangrui/frontend-slides](https://github.com/zarazhangrui/frontend-slides) · ⭐ 22,614

> Create beautiful slides on the web using Claude's frontend skills.

掀起这一波 HTML Slide Skill 浪潮的源头项目。核心理念是「Show, Don't Tell」——与其让你用文字描述审美偏好，不如直接生成视觉预览让你挑选。完全为不懂 CSS/JS 的人设计。

**16 个主题，三组分类：**

- **暗色系** — Bold Signal（高对比卡片）、Electric Studio（专业分屏）、Creative Voltage（复古现代 + 电光蓝霓虹）、Dark Botanical（暖色调高级感）。
- **浅色系** — Notebook Tabs（编辑风格 + 彩色标签纸）、Pastel Geometry（友好、纵向胶囊）、Split Pastel（双色纵向分割、俏皮）、Vintage Editorial（个性化几何）。
- **特色风格** — Neon Cyber（粒子背景 + 霓虹）、Terminal Green（开发者黑客风）、Swiss Modern（包豪斯极简）、Paper & Ink（首字下沉 + 引用突显）。

**亮点**：极舒服的「风格发现」流程；活跃的 fork 生态（见下方 [`frontend-slides-editable`](#9-archlizhengfrontend-slides-editable--362)）；Anthropic 官方将其作为 Skill 能力的展示案例。完整 demo 视频和资源见 [项目 README](https://github.com/zarazhangrui/frontend-slides)。

---

#### 2. [alchaincyf/huashu-design](https://github.com/alchaincyf/huashu-design) · ⭐ 19,547

> 《打字。回车。一份能交付的设计。》 —— Claude Code 里 HTML 原生的设计 Skill · Agent-agnostic · 20 设计哲学 · 5 维评审 · MP4 导出。

<p align="center">
  <a href="https://github.com/alchaincyf/huashu-design"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c2-slides-pptx-en.gif" width="720" alt="huashu-design — 一句话出 slides + 可编辑 PPTX"/></a>
  <br><sub>上图：一句话 → HTML deck + 可编辑 PPTX，约 15 分钟（取自项目 README 自带 demo）。</sub>
</p>

不是「AI 凑合能用」级别——产出看起来像真正的设计团队做的。把你的品牌资产（Logo、配色、UI 截图）丢给它，它会读懂你的品牌语气；什么都不给，内置的 20 套设计语言依然能让产出远离 AI 套路。

| 能力 | 交付物 | 典型耗时 |
| --- | --- | --- |
| 交互原型（App / Web） | 单文件 HTML · 真实 iPhone bezel · 可点击 · Playwright 验证 | 10–15 分钟 |
| **幻灯片** | **HTML deck（浏览器演示）+ 可编辑 PPTX（保留文本框）** | **15–25 分钟** |
| 动效设计 | MP4（25fps / 60fps 插帧）+ GIF（调色板优化）+ BGM | 8–12 分钟 |
| 设计变体 | 3+ 并列方案 · 实时参数微调 · 跨维度探索 | 10 分钟 |
| 信息图 / 数据可视化 | 印刷级排版 · 导出 PDF / PNG / SVG | 10 分钟 |
| 设计方向顾问 | 5 流派 × 20 哲学 · 推荐 3 个方向 · 并行生成 demo | 5 分钟 |
| 5 维专家评审 | 雷达图 + Keep / Fix / Quick Wins · 可执行打卡清单 | 3 分钟 |

安装：`npx skills add alchaincyf/huashu-design`。

---

#### 3. [op7418/guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) · ⭐ 18,604

> A Claude Code Skill that turns prompts into horizontal-swipe magazine-style HTML decks — 10 layouts, 5 curated themes, WebGL hero backgrounds, single-file output.

整个生态的「杂志风之声」。两个标志性风格一眼可辨：

- **Style A — 电子杂志 × 电子墨水**。Monocle 贴上代码。叙事、观点、分享、个人风格表达。
- **Style B — 瑞士国际主义**。网格至上、单一高饱和锚点色、直角、发丝线、极致字号对比。事实陈述、产品、分析、方法论表达。

**✅ 合适**：线下分享、行业内部讲话、私享会、AI 产品发布、demo day、强烈个人风格的演讲。
**❌ 不合适**：大段表格数据、培训课件（信息密度不够）、需多人协作编辑（静态 HTML）。

---

#### 4. [nicobailon/visual-explainer](https://github.com/nicobailon/visual-explainer) · ⭐ 8,837

> Agent skill that generates rich HTML pages or slide decks for diagrams, diff reviews, plan audits, data tables, and project recaps.

<p align="center">
  <a href="https://github.com/nicobailon/visual-explainer"><img src="https://raw.githubusercontent.com/nicobailon/visual-explainer/main/banner.png" width="720" alt="visual-explainer banner"/></a>
</p>

「瑞士军刀」式 Skill——同一个 Skill 可以输出单页 Landing Page、代码讲解 Deck、或 40 页的项目复盘。技术内容（diff review、plan audit、内联 SVG 图）尤其强。

**4 种主美学（默认暗色优先）：**

- **Midnight Editorial** — 深海军蓝 + 衬线标题 + 暖金点缀。彭博商业周刊遇上 Apple keynote。
- **Terminal Mono** — 暗色背景 + 全等宽字体 + 绿/青强调。开发者深度技术分享。
- **Warm Signal** — 米白纸感 + 粗体无衬线 + 赤陶/珊瑚卡片。Pitch 和总览。
- **Swiss Clean** — 纯白 + 几何无衬线 + 单色强调 + 可见网格。数据密集的分析型内容。

---

#### 5. [lewislulu/html-ppt-skill](https://github.com/lewislulu/html-ppt-skill) · ⭐ 6,411

> HTML PPT Studio — A world-class AgentSkill for producing professional HTML presentations.

<p align="center">
  <a href="https://github.com/lewislulu/html-ppt-skill"><img src="https://raw.githubusercontent.com/lewislulu/html-ppt-skill/main/docs/readme/hero.gif" width="720" alt="html-ppt-skill — hero with live previews"/></a>
  <br><sub>上图：项目 README 自带的 hero 循环——主题预览在实时切换。</sub>
</p>

目前为止特性最完备的 Skill。纯静态 HTML/CSS/JS，无 build step，自带演讲者模式（含像素级预览 + 演讲稿 + 计时器）。

- **36 主题** — `minimal-white`、`editorial-serif`、`soft-pastel`、`arctic-cool`、`catppuccin-latte`、`catppuccin-mocha`、`dracula`、`tokyo-night`、`nord`、`solarized-light`、`gruvbox-dark`、`rose-pine`、`neo-brutalism`、`glassmorphism`、`bauhaus`、`swiss-grid`、`xiaohongshu-white`、`aurora`、`blueprint`、`memphis-pop`、`cyberpunk-neon`、`y2k-chrome`、`retro-tv`、`japanese-minimal`、`vaporwave`、`midcentury`、`corporate-clean`、`academic-paper`、`news-broadcast`、`pitch-deck-vc`、`magazine-bold`、`engineering-whiteprint` 等。
- **15 套整 Deck 模板** — 8 套从真实演讲中提炼（`xhs-white-editorial`、`graphify-dark-graph`、`knowledge-arch-blueprint`、`hermes-cyber-terminal`、`obsidian-claude-gradient`、`testing-safety-alert`、`xhs-pastel-card`、`dir-key-nav-minimal`）+ 7 套场景化骨架（`pitch-deck`、`product-launch`、`tech-sharing`、`weekly-report`、`xhs-post` 3:4 九宫格、`course-module`、`presenter-mode-reveal` 🎤 每页 150–300 字演讲稿）。
- **31 种单页版式**、**47 种动画**（27 CSS + 20 canvas 特效）、**`S` 键演讲者模式**。

<p align="center">
  <a href="https://github.com/lewislulu/html-ppt-skill"><img src="https://raw.githubusercontent.com/lewislulu/html-ppt-skill/main/docs/readme/themes.png" width="720" alt="html-ppt-skill — 36 主题中的 8 个"/></a>
  <br><sub>36 主题中的 8 个。</sub>
</p>

---

#### 6. [1weiho/open-slide](https://github.com/1weiho/open-slide) · ⭐ 5,498

> 为 Agent 而生的 Slide 框架。用自然语言描述你的 Deck —— 编程 Agent 来写 React。open-slide 处理 canvas、缩放、导航、热重载、演示模式，让 Agent 专注于内容。

<p align="center">
  <a href="https://github.com/1weiho/open-slide"><img src="https://github.com/user-attachments/assets/02f5e6d7-12a7-4a8e-88e7-ae8770a96584" width="720" alt="open-slide cover"/></a>
</p>

架构上和 Tier S 其它项目都不一样——open-slide 是个**框架**，不是纯 Markdown Skill。每张 slide 渲染到固定 1920×1080 画布，每页都是任意 React 组件而非受限 DSL。脚手架内置了两个 Agent Skill（`/create-slide` 和 `/slide-authoring`），让整个写 Deck 的循环留在 Claude Code / Codex / Cursor 内部。

**亮点**

- 🤖 **Agent 原生写作** — `/create-slide` 端到端起草 Deck（问 4 个 scope 问题，挑 ID，写页面）；`/slide-authoring` 是画布、字阶、配色、版式规则的技术参考。
- 🎯 **浏览器内 inspector** — 开发模式下点击任意元素加注释（*「这里改红色」*、*「标题小一点」*）。注释以 `@slide-comment` 标记持久化在源码中；`/apply-comments` 让 Agent 一次性把所有注释落地。
- 🖼️ **资产管理器** + 内置 [svgl](https://svgl.app/) 品牌 Logo 检索。
- 🎬 **专业演讲模式** — 全屏 + 键盘导航 + 演讲者模式（当前/下一页预览 + 演讲稿 + 计时器）。
- 📦 **导出静态 HTML 和 PDF**，可一键部署到 Vercel / Cloudflare Pages / Netlify 等任意静态托管。

安装：`npx @open-slide/cli init my-slide`。

---

#### 7. [zarazhangrui/beautiful-html-templates](https://github.com/zarazhangrui/beautiful-html-templates) · ⭐ 3,096

> A library of HTML slide templates designed so any coding agent can pick the right one and produce a beautiful deck on the user's behalf, automatically.

<p align="center">
  <a href="https://github.com/zarazhangrui/beautiful-html-templates"><img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/soft-editorial-4.png" width="720" alt="soft editorial template"/></a>
  <br><sub>Soft Editorial —— 32 套模板中的一套，每套都有封面 · 中段 · 后段变体。</sub>
</p>

`frontend-slides` 的姊妹仓库——只有模板，没有 Skill 逻辑。32 套模板、每套 3 张幻灯片（封面 · 中段 · 后段），让 Agent 在提交方案前先看清每种视觉系统在不同版式职责下的表现。

同样列入下方的 [Templates](#templates) 章节。

---

### Tier A · 生产可用 / 100–1000 stars

成熟、持续维护、风格观点鲜明的 Skill。最适合「我已经知道要什么风格」的场景——例如「我要一份 McKinsey 风格的咨询 deck」——选一个专一做这件事且做得很好的 Skill。

---

#### 8. [mucsbr/ppt-agent-workflow-san](https://github.com/mucsbr/ppt-agent-workflow-san) · ⭐ 597

> 渐进交互式 PPT 生成 Skill。

<p align="center">
  <a href="https://github.com/mucsbr/ppt-agent-workflow-san"><img src="https://raw.githubusercontent.com/mucsbr/ppt-agent-workflow-san/main/1.png" width="720" alt="ppt-workflow 预览"/></a>
</p>

两阶段工作流，分散在子仓库中：

- `ppt-workflow/` — 生成 PPT 内容规划，导出 HTML 或 PNG 预览。
- `html-slide-to-pptx/` — 把结构化 HTML slide 转成可编辑 PPTX。

值得关注的是它把「HTML → PPTX 导出」当作一等公民处理，而不是事后补丁。

---

#### 9. [archlizheng/frontend-slides-editable](https://github.com/archlizheng/frontend-slides-editable) · ⭐ 362

> Editable HTML presentation skill for Codex / Claude Code with drag-resize editing, slide reordering, local save/export, and PPTX-to-web conversion.

<p align="center">
  <a href="https://github.com/archlizheng/frontend-slides-editable"><img src="https://raw.githubusercontent.com/archlizheng/frontend-slides-editable/main/docs/preset-previews/bold-signal-cover.png" width="260" alt="Bold Signal"/>&nbsp;<img src="https://raw.githubusercontent.com/archlizheng/frontend-slides-editable/main/docs/preset-previews/electric-studio-cover.png" width="260" alt="Electric Studio"/>&nbsp;<img src="https://raw.githubusercontent.com/archlizheng/frontend-slides-editable/main/docs/preset-previews/neon-cyber-cover.png" width="260" alt="Neon Cyber"/></a>
  <br><sub>三张预设封面 —— Bold Signal · Electric Studio · Neon Cyber。</sub>
</p>

`zarazhangrui/frontend-slides` 的可编辑 fork。完整保留上游的风格发现、视口纪律、PPT 转换能力，并在此之上加上完整的浏览器内编辑运行时：拖动对象、缩放区块、文本编辑、幻灯片重排、本地保存、导出干净的单文件 HTML。

> 真实演讲使用时仍应实现 `STYLE_PRESETS.md` 中每个 Preset 的签名级布局。编辑模式是增量能力，不是「所有美学共用一个 slide 原型」的许可证。

---

#### 10. [vigorX777/ppt-svg-generator](https://github.com/vigorX777/ppt-svg-generator) · ⭐ 238

> 将 Markdown 文稿快速转化为 HTML / PDF 演示文稿，支持多种预设风格。

<p align="center">
  <a href="https://github.com/vigorX777/ppt-svg-generator"><img src="https://github.com/user-attachments/assets/2454e688-d3b8-40a2-a3f8-893bbe5060ee" width="720" alt="ppt-svg-generator 预览"/></a>
</p>

| 风格 | 特点 | 适用场景 |
| --- | --- | --- |
| 极简主义 | 纯白高冷，大量留白，克莱因蓝点缀 | 产品发布、设计分享、TED 演讲 |
| 商务咨询 | 深蓝稳重，McKinsey 风，橙色强调 | 方案汇报、咨询报告、投资路演 |
| 科技暗黑 | 深色背景，霓虹渐变，玻璃拟态 | 技术分享、产品演示、黑客松 |
| 瑞士平面 | 强烈对比，包豪斯风，信号红 | 创意提案、品牌展示、艺术展示 |
| 品牌蓝 | 蓝紫青配色，现代专业 | 企业培训、通用演示、正式场合 |

---

#### 11. [likaku/Mck-ppt-design-skill](https://github.com/likaku/Mck-ppt-design-skill) · ⭐ 198

> 麦麸风格 PPT 设计系统。70 layout patterns, flat design, python-pptx。

<p align="center">
  <a href="https://github.com/likaku/Mck-ppt-design-skill"><img src="https://github.com/user-attachments/assets/075ec46d-dd73-4454-92d0-84184b78d276" width="380" alt="Mck 封面页"/>&nbsp;<img src="https://github.com/user-attachments/assets/3b25f071-8a81-48e3-a62b-9d9be9026f2e" width="380" alt="Mck 内容页"/></a>
</p>

AI 原生的 PowerPoint 设计系统——67 layouts · Harness Engineering · BLOCK_ARC charts · QA pipeline · Python runtime。是清单中观点最鲜明的 McKinsey/BCG 风 Skill；输出的是精炼的 PPTX 而非 HTML，适合受众期望 `.pptx` 但你又想要咨询级别字体细节的场景。

---

#### 12. [bytonylee/future-slide-skill](https://github.com/bytonylee/future-slide-skill) · ⭐ 135

> Reusable slide-generation skill for image-based and HTML-based AI workflows.

<p align="center">
  <a href="https://github.com/bytonylee/future-slide-skill"><img src="https://raw.githubusercontent.com/bytonylee/future-slide-skill/main/public/four-skill-flow.png" width="720" alt="future-slide-skill 流程"/></a>
</p>

少数几个能在「图片渲染幻灯片」（社交媒体九宫格场景）和「实时 HTML deck」之间，使用同一份内容 IR 干净切换的 Skill 之一。

---

### Tier B · 新兴 / 专精方向

星标数较小，但其中不少是各自专精领域里**最佳**的选择——华为式战略页、面向知识留存的教学幻灯片、Anti-AI-Slop 的 token 化设计系统等。

---

#### 13. [Akxan/ppt-agent-skill](https://github.com/Akxan/ppt-agent-skill) · ⭐ 91

> 🎨 World-class AI presentation generator · 26 styles · 18 charts · benchmarked against Linear / Anthropic / Stripe / Apple / NYT.

<p align="center">
  <a href="https://github.com/Akxan/ppt-agent-skill"><img src="https://raw.githubusercontent.com/Akxan/ppt-agent-skill/main/assets/hero-all.png" width="720" alt="Akxan hero — 26 styles"/></a>
</p>

模拟万元/页 PPT 设计公司的完整工作流，把一句话变成专业级演示文稿。不是「给个大纲套模板」，而是先调研后生成 / 内容驱动版式 / 全局风格一致 / 真实数据填充的完整管线。

每个风格的视觉水准对标实际世界级品牌的官网/产品页排版做法——不是参考截图，是参考实际 CSS 实现——字距铁律 / tabular-nums / OpenType 特性 / serif italic 混排 / 字体栈三层降级。

**风格家族**：

- 暗色专业 — 7 风格（`references/styles/dark.md`）
- 浅色高级 — 8 风格（`references/styles/light.md`）
- 活力鲜明 — 4 风格（`references/styles/vibrant.md`）
- 东方文化 — 3 风格（`references/styles/cultural.md`）
- 自然/复古 — 4 风格（`references/styles/natural.md`）

---

#### 14. [edu-ai-builders/visual-cognition-slides](https://github.com/edu-ai-builders/visual-cognition-slides) · ⭐ 72

> 基于认知科学与教学设计的 HTML slides 生成工具。面向教师、研究者与内容创作者，输出针对知识留存优化的演示文稿。

这个 Skill 的每一个决策——叙事结构、每张 slide 的版式、每个动画——都来自同一个问题：**观众在这里需要完成什么认知动作？**

这不是设计工具，是教学设计工具。

**最适合**：教师、研究者、博士生——需要有效传递知识，不只是「好看」；内容创作者——口播视频、科普系列、知识类账号；做分享、演讲、内部培训的人。
**不太适合**：纯商业演示（PowerPoint / Keynote 更快）；需要实时协作编辑（Google Slides 更合适）。

---

#### 15. [software-ai-life/Awesome-PPT-Design-Skills](https://github.com/software-ai-life/Awesome-PPT-Design-Skills) · ⭐ 56

> Agent 无关的 PPT 设计 Skill 集合，搭配 [ppt-master](https://github.com/hugohe3/ppt-master) 输出精致 PowerPoint。

不是单个 Skill，而是 meta 集合。作者把多种不同视觉系统（`japanese-style-ppt-skill`、`soft-3d-clay-ppt-skill`、`futuristic-tech-editorial-ppt-skill`、`minimalist-luxury-branding-ppt-skill`、`modern-illustration-editorial-ppt-skill`、`japanese-hand-drawn-editorial-ppt-skill`）打包成稳定的视觉层，让你在不同的 Agent（Codex、Claude Code、Cursor、OpenCode、OpenClaw、Hermes）上得到一致的产出。繁体中文是 first-class 支持。

同样列入下方 [Templates](#templates) 章节。

---

#### 16. [WayneZhon/KingDee-PPT-Skill](https://github.com/WayneZhon/KingDee-PPT-Skill) · ⭐ 54

> 将文字、大纲、文档一键转换为金蝶官方风格 .pptx 或交互式 HTML 幻灯片。

完全复现金蝶国际软件集团 2026 版官方模板设计语言。双风格体系（Classic / Bento Motion），29 种版式，7 种思维模型自动识别，内嵌官方背景与 Logo，零配置可用。

---

#### 17. [kaisersong/slide-creator](https://github.com/kaisersong/slide-creator) · ⭐ 44

> A skill for Claude Code and OpenClaw that generates stunning, zero-dependency HTML presentations.

<p align="center">
  <a href="https://github.com/kaisersong/slide-creator"><img src="https://raw.githubusercontent.com/kaisersong/slide-creator/main/demos/screenshots/bold-signal.png" width="380" alt="Bold Signal demo"/>&nbsp;<img src="https://raw.githubusercontent.com/kaisersong/slide-creator/main/demos/screenshots/electric-studio.png" width="380" alt="Electric Studio demo"/></a>
</p>

- **IR 优先工作流** — `--plan` 蒸馏出 `BRIEF.json`，`--generate` 基于 IR 渲染。
- **两档规划深度** — Auto 求速度，Polish 锁叙事 + 视觉。
- **内容审核系统** — 16 个 checkpoint；`--review` 按需诊断；Polish 模式自动跑 review；三类规则（hard / context-aware / advisory）。
- **22 个设计预设**，每个都带具名的版式变体。
- **内容类型自动路由** — 自动为 pitch deck、开发者工具、数据报告推荐风格。
- **风格发现** — 在确认之前生成 3 个视觉预览。
- **内联 SVG 图表** — 流程图、时间线、柱状图、对比网格、组织架构图，无任何外部库。
- **Blue Sky 起手模板** — 完整脚手架，避免模型误实现视觉系统。

---

#### 18. [FeeiCN/slide-writer](https://github.com/FeeiCN/slide-writer) · ⭐ 37

> A slide-writing skill for generating enterprise HTML presentations from ideas, outlines, documents, and speech drafts.

<p align="center">
  <a href="https://github.com/FeeiCN/slide-writer"><img src="https://raw.githubusercontent.com/FeeiCN/slide-writer/main/examples/slide-writer.png" width="720" alt="slide-writer 示例"/></a>
</p>

- **任何输入 → 企业级 deck** — 一句话、大纲、演讲稿、笔记、已有 HTML 都可以。
- **14 套品牌主题，自动识别** — Ant Group、Alibaba、Tencent、ByteDance 等。提及关键词，对应的主题、Logo、配色自动应用。
- **单文件交付** — 一个独立 HTML 文件，CSS / JS / 图片全部内联，任何浏览器都能打开。无需 PowerPoint、Keynote、任何依赖。
- **始终最新** — 每次运行时自动拉取最新的主题、组件和生成规则。

---

#### 19. [zuiho-kai/huawei-style-ppt-skill](https://github.com/zuiho-kai/huawei-style-ppt-skill) · ⭐ 35

> 华为风格 PPT Skill — 高密度信息 PPT 制作工作流。

<p align="center">
  <a href="https://github.com/zuiho-kai/huawei-style-ppt-skill"><img src="https://raw.githubusercontent.com/zuiho-kai/huawei-style-ppt-skill/master/docs/demo-1.jpg" width="720" alt="华为风 demo"/></a>
</p>

从需求到交付的高密度信息型 PPT 完整工作流 Skill，特别适合华为式战略页、架构总览、数据洞察、方案对比等高密度 document 型页面。

---

#### 20. [codesstar/next-slide](https://github.com/codesstar/next-slide) · ⭐ 34

> 你的下个 slide，何必是 PPT — AI-powered HTML presentations. 26+ styles, zero dependencies, bilingual.

每种风格都是一个完整设计系统：精选字体、配色板、版式范式、签名级动画、响应式断点。

| 分类 | 数量 | 风格 | 调性 |
| --- | --- | --- | --- |
| Dark | 11 | Keynote Noir, Bold Signal, Neon Cyber, Terminal Green, Midnight Corporate, Cinema Scope, Dark Botanical, Starfield, Dark Premium, Dark Cinema, Futuristic Blue | 大会、发布、技术演讲 |
| Light | 11 | Swiss Modern, Paper & Ink, Notebook Tabs, Pastel Geometry, Morning Brief, Campus White, Soft Landing, Watercolor Wash, Korean Soft, Claymorphism 3D, Wabi-Sabi Zen | 学术、商务、教学 |
| Editorial | 4 | Editorial Serif, Fashion Editorial, Newsprint Broadsheet, Vintage Editorial | 杂志风、行业洞察 |
| Bold | 7 | Electric Studio, Creative Voltage, Split Pastel, Pop Art, Bold Typography, Neon Brutalism, Memphis Pop | 初创团队、创意提案 |
| Retro | 5 | Grainy Retro, Art Deco Gatsby, Risograph Overprint, Vintage Poster, Retro Arcade | 怀旧风、风格化 |
| Artistic | 7 | Surrealism Gallery, Scrapbook Portfolio, Blue Collage, Pink Handwritten, Art Nouveau Botanical, Soft Dreamy, Terracotta Earth | 艺术、设计、作品集 |
| Cultural | 8 | 东方墨韵, 和風, Gradient Dreams, Blueprint, Bauhaus Primary, Swiss Grid, Aurora Mesh, Chinese Ink Wash | 文化活动、主题演讲 |

---

#### 21. [Phlegonlabs/Powerpoint-fancy-design](https://github.com/Phlegonlabs/Powerpoint-fancy-design) · ⭐ 25

> A presentation-design skill for Codex and Claude Code that turns page-structured Markdown into styled 1600x900 HTML slides, PNG renders, and exportable PPTX decks.

<p align="center">
  <a href="https://github.com/Phlegonlabs/Powerpoint-fancy-design"><img src="https://raw.githubusercontent.com/Phlegonlabs/Powerpoint-fancy-design/main/assets/style-preview-a.png" width="720" alt="Swiss International 预览"/></a>
</p>

**使用场景**：

- 商务 / 政策类 deck，需要克制的层级和适合演讲的字体设计。
- 品牌 / 文化 / 展览类 deck，需要比标准模板更强的视觉方向。
- 中文及中英双语演讲，需要 style-aware 的字体配对而不是 fallback。
- 静态 HTML 转 PPT 的工作流，更看重最终视觉保真而不是可编辑的 PPT 原生对象。

---

#### 22. [xhshow2025/-PPT-sense-deck-skill-](https://github.com/xhshow2025/-PPT-sense-deck-skill-) · ⭐ 22

> 鲸格 PPT — Codex Skill，用于生成高质量浏览器原生演示文稿。

以静态 HTML/CSS/JS 为主要产物，构建了完整流水线：内容 IR、主题系统、完整 Deck 模板、单页布局、动画运行时、演讲者模式、可编辑模式、手势控制、导出辅助。

**特色主题**：

- `apple-bento-glass` — AI、产品策略、新品类、精品商业 Deck。
- `executive-clean` — 董事会、战略汇报、投资人更新、周报。
- `semantic-dark` — 技术分享、架构讲解、AI 系统、开发者演示。
- `xhs-editorial` — 小红书图文、社交媒体 carousel、消费教育内容。
- `cyber-neon` — Demo Day、产品展示、RGB 硬件、赛博发布会。
- `warm-paper` — 课程、讲义、故事、文化主题。
- `nordic-childrens-picture-book` — 北欧儿童绘本风、怀旧幽默故事。
- 史诗级 — 历史文化叙事、昭君出塞、国风电影感展示。
- `neon-noir-city` — 赛博朋克城市、AI 未来生活、2098 叙事。

---

#### 23. [nghiahsgs/skills-slides](https://github.com/nghiahsgs/skills-slides) · ⭐ 22

> 50,000+ unique HTML presentation designs. Zero dependencies. Anti-AI-slop. A Claude Code skill.

<p align="center">
  <a href="https://github.com/nghiahsgs/skills-slides"><img src="https://raw.githubusercontent.com/nghiahsgs/skills-slides/main/examples/screenshots/slide-06-features.png" width="720" alt="skills-slides features 页"/></a>
</p>

用一套 **token 化设计系统** 和严格的 **anti-slop checklist**，在产物交付之前拦截掉「一眼 AI 味」的通用套路。最终产物：看起来像是被认真设计过，而不是套模板拼出来的。

- **50 种美学** — `startup-pitch`、`neon-cyber`、`editorial-minimal`、`luxury-noir`、`consulting-swiss`、`vaporwave`、`terminal-hacker`、`ai-ml-showcase` 等。每种美学定义兼容的配色、字体、版式、签名级特效。
- **20 套配色** — `midnight-aurora`、`crimson-signal`、`electric-indigo`、`rose-gold`、`arctic-frost`、`carbon-fiber`。每套都附 WCAG 对比度。
- **10 套字体** — Google Fonts 和 Fontshare 的 Display + Body 配对（`clash-satoshi`、`fraunces-worksans`、`syne-spacemono`、`bodoni-dmsans`）。
- **30+ 特效** — 完整 CSS+JS 片段，附性能影响标签：`particle-bg`、`gradient-mesh`、`aurora-flow`、`grid-overlay`、`glassmorphism`、`noise-texture`、`magnetic-cursor`。

---

## Templates

手工打磨的 HTML 模板库——丢进项目，让 Agent 指向这个目录，就能生成 deck。

---

#### T1. [zarazhangrui/beautiful-html-templates](https://github.com/zarazhangrui/beautiful-html-templates) · ⭐ 3,096

> A library of HTML slide templates designed so any coding agent can pick the right one and produce a beautiful deck on the user's behalf, automatically.

<p align="center">
  <a href="https://github.com/zarazhangrui/beautiful-html-templates"><img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/vellum-1.png" width="260" alt="Vellum 封面"/>&nbsp;<img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/stencil-tablet-1.png" width="260" alt="Stencil Tablet 封面"/>&nbsp;<img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/neo-grid-bold-1.png" width="260" alt="Neo Grid Bold 封面"/></a>
  <br><sub>32 套模板中的三套 —— Vellum · Stencil Tablet · Neo Grid Bold。</sub>
</p>

**32 套模板**，每套 3 张（封面 · 中段 · 后段），让 Agent 在做选择前先看清每种视觉系统在不同版式职责下的真实表现。Claude Code Skill 生态事实上的模板基准库——上方的不少 Skill 都会直接引用或借鉴这些模板。

---

#### T2. [software-ai-life/Awesome-PPT-Design-Skills](https://github.com/software-ai-life/Awesome-PPT-Design-Skills) · ⭐ 56

> Agent 无关的 PPT 设计 Skill 集合，以多风格模板库的形式发布。

当你不想被锁定在一种美学上时，它就是一个多风格模板库：

- **japanese-style-ppt-skill** — 日本風格高端編輯簡報，包含兩種 house style：
  - *Washi Paper & Soft Glow* — 和紙感米白背景、柔和微光與低彩度色系、細灰線、靛藍克制點綴、大量留白但有溫度。
  - *Japanese Lifestyle Editorial* — 純白背景、焦橙與深炭灰、高端生活雜誌式排版、非對稱壓邊圖片與結構化 grid。
- **soft-3d-clay-ppt-skill** — Claymorphism 風格。暖米色 `#FDF5E6`、鼠尾草綠 `#B2AC88`、莫蘭迪粉 `#DBADAD`、柔霧感幾何形狀。
- **futuristic-tech-editorial-ppt-skill** — 未來科技雜誌風。純白 `#FFFFFF`、電光藍 `#2F6BFF`、石墨灰 `#2B2B2B`、細線 grid、資料感模組、無陰影無 3D。
- **minimalist-luxury-branding-ppt-skill** — 高端品牌提案。暖米色 `#F5EFE6`、柔棕色 `#A68A64`、深灰文字 `#3A3A3A`、襯線標題 + 無襯線內文、精品感節奏。
- **modern-illustration-editorial-ppt-skill** — 現代插畫型高端編輯簡報。柔米色 `#F7F3EE`、霧藍 `#A7C7E7`、灰橘 `#E8A87C`、炭灰 `#2F2F2F`、柔和向量插畫。
- **japanese-hand-drawn-editorial-ppt-skill** — 日系手繪編輯簡報。暖白紙感 `#F8F6F2`、墨黑線條 `#2B2B2B`、柔灰 `#BDBDBD`、低彩靛藍 `#6C7A89`、鉛筆/墨線插畫 + 淡水彩。

---

## 贡献指南

欢迎提 PR——见 [CONTRIBUTING.md](CONTRIBUTING.md)。基本门槛：

1. 仓库公开、采用 MIT / Apache / CC 一类开源协议、且包含真实可运行的代码（Skill 清单文件 / 模板目录，不能只有 README）。
2. 输出以 HTML 为先（PPTX 导出 ok，但 HTML 必须是 source of truth）。
3. 星标数在 PR 合并时核对，并据此放到对应 Tier。
4. 如果你的项目 README 里有 demo GIF、banner、或截图网格，请在条目中加上 `<p align="center"><img></p>` 并指向原始资源 URL —— 参考现有条目的格式。

发现链接失效、星标过期、或我们漏掉的项目？欢迎 [提 Issue](https://github.com/ToseaAI/awesome-html-slide-skills/issues/new)。

---

## License

本仓库中由我们整理的内容（这份 README、整体结构、描述性文字）采用 [CC BY 4.0](LICENSE) 协议。各被收录项目保留各自原协议，使用前请检查对应仓库的 License。

内联预览图均通过 `raw.githubusercontent.com` 或 `github.com/user-attachments` 热链自各项目自身的 GitHub 仓库，版权归原作者所有，仅作为帮助读者一眼识别项目的合理使用缩略图。如你是被收录项目的作者，希望移除或替换预览图，请 [提 Issue](https://github.com/ToseaAI/awesome-html-slide-skills/issues/new)，我们会立刻处理。

---

<p align="center">
  由 <a href="https://tosea.ai"><b>Tosea.ai</b></a> 维护 · <a href="https://tosea.ai/slide-skills">在网页上浏览</a> · <a href="https://github.com/ToseaAI/awesome-gpt-image-2-prompts">同系列：awesome-gpt-image-2-prompts</a>
</p>
