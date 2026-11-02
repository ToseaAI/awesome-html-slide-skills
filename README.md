<h1 align="center">Awesome HTML Slide Skills</h1>

<p align="center"><i>The definitive list of agent skills and template libraries for generating beautiful, single-file HTML presentations — for Claude Code, Codex, Cursor, OpenClaw, and Hermes.</i></p>

<p align="center">
  <a href="LICENSE"><img alt="License: CC BY 4.0" src="https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg"></a>
  <a href="https://tosea.ai/slide-skills"><img alt="Live on Tosea.ai" src="https://img.shields.io/badge/Live%20on-Tosea.ai-000000?style=flat&logo=safari&logoColor=white"></a>
  <a href="https://tosea.ai"><img alt="Made by Tosea.ai" src="https://img.shields.io/badge/Made%20by-Tosea.ai-000000?style=flat"></a>
  <a href="https://github.com/ToseaAI/awesome-html-slide-skills/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/ToseaAI/awesome-html-slide-skills?style=flat&color=yellow"></a>
  <a href="https://github.com/ToseaAI/awesome-html-slide-skills/network/members"><img alt="GitHub forks" src="https://img.shields.io/github/forks/ToseaAI/awesome-html-slide-skills?style=flat&color=blue"></a>
  <a href="https://awesome.re"><img alt="Awesome" src="https://awesome.re/badge-flat2.svg"></a>
</p>

<p align="center"><b>English</b> · <a href="README.zh-CN.md">中文</a></p>

A curated, open-source list of **HTML slide generation skills** — packaged agent skills (Claude Code / Codex / Hermes / OpenClaw / Cursor) and template libraries that turn one prompt, outline, or markdown file into a polished, zero-dependency, single-file HTML presentation.

Every entry below is a real, publicly available GitHub repository. Stars are pulled fresh from the GitHub API and used as the sole ordering signal. Descriptions, feature highlights, and inline previews are drawn from each project's own README — credit to the original authors.

> **Browse it on the web → [tosea.ai/slide-skills](https://tosea.ai/slide-skills).** Same curation, rendered as a faster-to-scan gallery with live GitHub stats. This README is the source of truth; the web page mirrors it.

> **Maintained by [Tosea.ai](https://tosea.ai)** — we build AI-native presentation tooling. If you ship an HTML slide skill or template library, [open a PR](CONTRIBUTING.md) and we'll add it.

---

## Featured Showcase

A glance at what these skills actually produce. Every preview below is the linked project's own demo — click an image to jump to that entry.

<table align="center"><tr>
<td align="center" width="25%"><a href="#3-alchaincyfhuashu-design---28440"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c2-slides-pptx-en.gif" width="220" alt="huashu-design — slides + PPTX export"/></a><br><sub><b>huashu-design</b><br>28.4k ⭐</sub></td>
<td align="center" width="25%"><a href="#4-nicobailonvisual-explainer---10739"><img src="https://raw.githubusercontent.com/nicobailon/visual-explainer/main/banner.png" width="220" alt="visual-explainer banner"/></a><br><sub><b>visual-explainer</b><br>10.7k ⭐</sub></td>
<td align="center" width="25%"><a href="#5-chuspeeismdashi-ppt-skill---10258"><img src="https://github.com/chuspeeism/dashi-ppt-skill/releases/download/readme-assets-v1/hero-result.gif" width="220" alt="dashi-ppt-skill — deck with per-page console"/></a><br><sub><b>dashi-ppt-skill</b><br>10.3k ⭐</sub></td>
<td align="center" width="25%"><a href="#6-open-slideopen-slide---9612"><img src="https://github.com/user-attachments/assets/02f5e6d7-12a7-4a8e-88e7-ae8770a96584" width="220" alt="open-slide cover"/></a><br><sub><b>open-slide</b><br>9.6k ⭐</sub></td>
</tr><tr>
<td align="center" width="25%"><a href="#7-lewisluluhtml-ppt-skill---8943"><img src="https://raw.githubusercontent.com/lewislulu/html-ppt-skill/main/docs/readme/hero.gif" width="220" alt="html-ppt-skill hero"/></a><br><sub><b>html-ppt-skill</b><br>8.9k ⭐</sub></td>
<td align="center" width="25%"><a href="#11-archlizhengfrontend-slides-editable---547"><img src="https://raw.githubusercontent.com/archlizheng/frontend-slides-editable/main/docs/preset-previews/bold-signal-cover.png" width="220" alt="bold-signal cover preset"/></a><br><sub><b>frontend-slides-editable</b><br>547 ⭐</sub></td>
<td align="center" width="25%"><a href="#12-likakumck-ppt-design-skill---328"><img src="https://github.com/user-attachments/assets/075ec46d-dd73-4454-92d0-84184b78d276" width="220" alt="Mck-ppt-design cover slide"/></a><br><sub><b>Mck-ppt-design-skill</b><br>328 ⭐</sub></td>
<td align="center" width="25%"><a href="#t1-zarazhangruibeautiful-html-templates---4914"><img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/soft-editorial-4.png" width="220" alt="soft editorial template"/></a><br><sub><b>beautiful-html-templates</b><br>4.9k ⭐</sub></td>
</tr></table>

---

## Contents

- [About this list](#about-this-list)
- [Skills](#skills)
  - [Tier S · Foundational / 1k+ stars](#tier-s--foundational--1k-stars)
  - [Tier A · Production-ready / 100–1000 stars](#tier-a--production-ready--1001000-stars)
  - [Tier B · Emerging / specialized](#tier-b--emerging--specialized)
- [Export to editable PowerPoint (PPTX)](#export-to-editable-powerpoint-pptx)
- [Templates](#templates)
- [Contributing](#contributing)
- [License](#license)

---

## About this list

**What counts as an "HTML slide skill"?**

A skill is a self-contained package — usually a `SKILL.md`, a folder of reference styles, and a small runtime — that an AI coding agent can load to produce a finished HTML deck. Most projects below target Claude Code's [Agent Skills](https://docs.claude.com/en/docs/claude-code/skills) format, but many are agent-agnostic and work with Codex, Cursor, OpenClaw, Hermes, or anything that can read a markdown instruction file.

**Skills vs. templates.**

- **Skills** (the primary focus of this list) are *generative*: the agent writes the deck from your prompt, your outline, or your document, picking layouts and themes intelligently. They include planning logic, content routing, anti-AI-slop checks, and full design systems.
- **Templates** are *static*: hand-crafted HTML/CSS scaffolds you (or an agent) can copy and fill in. Smaller in scope, but extremely useful as the visual ground truth that skills reference.

**Why this list exists.**

HTML decks have quietly become the format of choice for AI-generated presentations: they render anywhere, embed anything, version-control cleanly, and never crash a board meeting because PowerPoint couldn't find a font. The ecosystem exploded in early 2026 — we counted 20+ serious skill packages in two months — but no one had collected them in one place. This is that place.

---

## Skills

> Ordered by GitHub star count, descending. Star counts last refreshed 2026-11-02.
> Tier cutoffs are heuristics, not value judgments — a 66-star skill targeting Huawei-style decks is probably more useful for that use case than a 31k-star generalist.

### Tier S · Foundational / 1k+ stars

These are the projects most of the others reference, fork, or benchmark against. If you're new to HTML slide skills, start here.

---

#### 1. [zarazhangrui/frontend-slides](https://github.com/zarazhangrui/frontend-slides) · ⭐ 31,722

> Create beautiful slides on the web using a coding agent's frontend skills.

The project that kicked off the modern HTML-slide-skill wave. Built on a "show, don't tell" philosophy: instead of asking you to describe your aesthetic preferences in words, it generates visual previews and lets you pick what you like. Designed so non-designers can produce decks without ever touching CSS or JavaScript.

**Themes (16, grouped by feel)**

- **Dark** — Bold Signal (vibrant card on dark), Electric Studio (clean split-panel), Creative Voltage (retro-modern electric blue + neon), Dark Botanical (elegant with warm accents).
- **Light** — Notebook Tabs (editorial, paper with colorful tabs), Pastel Geometry (vertical pills, friendly), Split Pastel (playful two-color vertical split), Vintage Editorial (witty, geometric shapes).
- **Specialty** — Neon Cyber (particle bg, neon glow), Terminal Green (hacker aesthetic), Swiss Modern (Bauhaus-inspired), Paper & Ink (drop caps and pull quotes).

**Why it stands out**: ergonomic style-discovery flow, a healthy fork ecosystem (see [`frontend-slides-editable`](#11-archlizhengfrontend-slides-editable---547) below), and Anthropic itself uses the project as an example of what skills can do. The full demo video and additional assets live on the [project's README](https://github.com/zarazhangrui/frontend-slides).

---

#### 2. [op7418/guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) · ⭐ 29,109

> AI-agent Skill for generating polished HTML slide decks: editorial magazine and Swiss layouts, image prompts, social covers, and a WebGL/low-power presentation runtime.

<p align="center">
  <a href="https://github.com/op7418/guizang-ppt-skill"><img src="https://github.com/user-attachments/assets/8960e78c-69bb-4b7e-aa95-6fad64b70314" width="720" alt="guizang-ppt-skill — Style B, Swiss International"/></a>
  <br><sub>Style B — Swiss International (from the project's README).</sub>
</p>

The "magazine voice" of the ecosystem. Two flagship styles you'll recognize on sight:

- **Style A — 电子杂志 × 电子墨水**. Monocle meets code. Narrative, opinion, sharing, personal-voice talks.
- **Style B — 瑞士国际主义**. Grid-first, single high-saturation anchor color, hairline rules, extreme type-scale contrast. Product launches, analysis, methodology.

Output is a single-file, horizontal-swipe HTML deck with built-in rehearsal and presenter modes; the skill also produces slide illustrations and multi-platform covers. The same author packages it, together with sibling card and page-layout skills, as a DeepSeek Harness plugin: [op7418/dsh-guizang-design](https://github.com/op7418/dsh-guizang-design).

**Fits**: offline sharing, industry-internal talks, private salons, AI product launches, demo day, speaker-led personal-style talks.
**Doesn't fit**: dense tabular data, training materials (too low-density), real-time collaborative editing (static HTML).

---

#### 3. [alchaincyf/huashu-design](https://github.com/alchaincyf/huashu-design) · ⭐ 28,440

> *"Type. Hit enter. A finished design lands in your lap."* — HTML-native design skill for Claude Code, Codex, Cursor & any agent · editable PPTX · MP4 export.

<p align="center">
  <a href="https://github.com/alchaincyf/huashu-design"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c2-slides-pptx-en.gif" width="720" alt="huashu-design — sentence to slides + editable PPTX"/></a>
  <br><sub>Above: one sentence → HTML deck + editable PPTX in ~15 min (the README's own demo).</sub>
</p>

Not "decent for AI" quality — the output looks like a real design team made it. Give it your brand assets (logo, colors, UI screenshots) and it reads your brand voice; give it nothing and, since 3.0, it sketches six thumbnails and develops the three strongest directions, drawing on a style library of 80+ styles, each with a visual specimen.

| Capability | Deliverable | Typical time |
| --- | --- | --- |
| Interactive prototype (App / Web) | Single-file HTML · real iPhone bezel · clickable · Playwright-verified | 10–15 min |
| **Slide decks** | **HTML deck (browser presentation) + editable PPTX (text frames preserved)** | **15–25 min** |
| Motion design | MP4 (25fps / 60fps interpolation) + GIF (palette-optimized) + BGM | 8–12 min |
| Design variations | 3+ side-by-side · live param tweaks · cross-dimension exploration | 10 min |
| Infographic / data viz | Print-quality typography · exports to PDF / PNG / SVG | 10 min |
| Xiaohongshu carousel / cover | 3:4 image sets (≤18) · 8 paradigm templates · continuous panorama strips · one-command slicing with checks | 10–15 min |
| Design direction advisor | Three logics × two candidates each · six thumbnails → three real designs, the other three kept as alternates | 10 min |
| 5-dimension expert critique | Radar chart + Keep / Fix / Quick Wins · actionable punch list | 3 min |

Install: `npx skills add alchaincyf/huashu-design`.

---

#### 4. [nicobailon/visual-explainer](https://github.com/nicobailon/visual-explainer) · ⭐ 10,739

> Agent skill that generates rich HTML pages or slide decks for diagrams, diff reviews, plan audits, data tables, and project recaps.

<p align="center">
  <a href="https://github.com/nicobailon/visual-explainer"><img src="https://raw.githubusercontent.com/nicobailon/visual-explainer/main/banner.png" width="720" alt="visual-explainer banner"/></a>
</p>

A "Swiss army knife" skill — it'll happily produce a single landing page, a code-walkthrough deck, or a 40-slide project recap. Especially strong on technical content: diff reviews, plan audits, and inline SVG diagrams.

**Aesthetics (4, dark-first by default)**

- **Midnight Editorial** — Deep navy, serif display, warm gold accents. Bloomberg Businessweek meets Apple keynote.
- **Terminal Mono** — Dark background, monospace everything, green/cyan accents. Developer-native deep-dives.
- **Warm Signal** — Cream paper background, bold sans, terracotta/coral cards. Pitches and overviews.
- **Swiss Clean** — White, geometric sans, single accent color, visible grid. Data-heavy analytical content.

---

#### 5. [chuspeeism/dashi-ppt-skill](https://github.com/chuspeeism/dashi-ppt-skill) · ⭐ 10,258

> An AI-agent skill that generates browser-editable presentations from multiple visual themes, exportable to HTML, PDF, and PPTX.

<p align="center">
  <a href="https://github.com/chuspeeism/dashi-ppt-skill"><img src="https://github.com/chuspeeism/dashi-ppt-skill/releases/download/readme-assets-v1/hero-result.gif" width="720" alt="dashi-ppt-skill — generated deck with per-page console"/></a>
  <br><sub>Above: a generated deck and its per-page editing console (from the project's README).</sub>
</p>

The output is the editor: every page of the generated deck carries its own console — sliders, toggles and dropdowns to switch layouts, change how many modules a page shows, swap palettes or shift the page's emphasis — and any text can be clicked and edited in place. Aimed at work decks (research, reviews, proposals, pitch decks) rather than pixel-level custom design.

- **12 visual themes**, **1,020 layout pages** across 20 page roles (cover, TOC, metrics, trends, comparison, flow, risks, ending…), **8,576 tunable controls**.
- **Charts and analysis frameworks** as ready-made layouts — radar, waterfall, treemap, funnel, heatmap, Sankey, Gantt, plus SWOT, Porter's Five Forces, PEST, Business Model Canvas and Double Diamond.
- **Media slots** — click or drag to replace images and video; text-only sources get image placeholders automatically.
- **One-click export** to an offline HTML bundle, PDF, or editable PPTX (needs a local Chrome / Chromium / Edge).

Install: `npx dashi-ppt-skill@latest` (Node.js 20+). Licensed AGPL-3.0.

---

#### 6. [open-slide/open-slide](https://github.com/open-slide/open-slide) · ⭐ 9,612

> The slide framework built for agents. Describe your deck in natural language — your coding agent writes the React. open-slide handles the canvas, scaling, navigation, hot reload, and present mode so the agent can focus on content.

<p align="center">
  <a href="https://github.com/open-slide/open-slide"><img src="https://github.com/user-attachments/assets/02f5e6d7-12a7-4a8e-88e7-ae8770a96584" width="720" alt="open-slide cover"/></a>
</p>

Architecturally different from most of Tier S — open-slide is a **framework**, not a pure markdown skill. Every slide renders into a fixed 1920×1080 canvas as an arbitrary React component, not a constrained DSL. The scaffolder ships with two agent skills (`/create-slide` and `/slide-authoring`) so the deck-authoring loop stays inside Claude Code / Codex / Cursor. (The repo moved from `1weiho/open-slide` to the `open-slide` organization.)

**Highlights**

- 🤖 **Agent-native authoring** — `/create-slide` drafts a deck end-to-end (asks four scoping questions, picks an id, writes the pages); `/slide-authoring` is the technical reference for canvas, type-scale, palette, and layout rules.
- 🎯 **In-browser inspector** — click any element in dev to attach a comment (*"make this red"*, *"shrink the headline"*). Comments persist as `@slide-comment` markers; `/apply-comments` lets the agent apply them all in one pass.
- 🖼️ **Assets manager** with built-in [svgl](https://svgl.app/) brand-logo search.
- 🎬 **Professional present mode** — fullscreen, keyboard navigation, presenter mode with current/next slide preview, speaker notes, timer.
- 📦 **Export to static HTML & PDF**, deploy-friendly to Vercel / Cloudflare Pages / Netlify / any static host.

Install: `npx @open-slide/cli init my-slide`.

---

#### 7. [lewislulu/html-ppt-skill](https://github.com/lewislulu/html-ppt-skill) · ⭐ 8,943

> HTML PPT Studio — A world-class AgentSkill for producing professional HTML presentations.

<p align="center">
  <a href="https://github.com/lewislulu/html-ppt-skill"><img src="https://raw.githubusercontent.com/lewislulu/html-ppt-skill/main/docs/readme/hero.gif" width="720" alt="html-ppt-skill — hero with live previews"/></a>
  <br><sub>Above: hero loop from the project's README — live previews cycling through themes.</sub>
</p>

By far the most feature-loaded skill on this list. Pure static HTML/CSS/JS, no build step, true presenter mode with pixel-perfect previews + speaker script + timer.

- **36 themes** — `minimal-white`, `editorial-serif`, `soft-pastel`, `arctic-cool`, `catppuccin-latte`, `catppuccin-mocha`, `dracula`, `tokyo-night`, `nord`, `solarized-light`, `gruvbox-dark`, `rose-pine`, `neo-brutalism`, `glassmorphism`, `bauhaus`, `swiss-grid`, `xiaohongshu-white`, `aurora`, `blueprint`, `memphis-pop`, `cyberpunk-neon`, `y2k-chrome`, `retro-tv`, `japanese-minimal`, `vaporwave`, `midcentury`, `corporate-clean`, `academic-paper`, `news-broadcast`, `pitch-deck-vc`, `magazine-bold`, `engineering-whiteprint`, and more.
- **15 full-deck templates** — 8 extracted from real-world decks (`xhs-white-editorial`, `graphify-dark-graph`, `knowledge-arch-blueprint`, `hermes-cyber-terminal`, `obsidian-claude-gradient`, `testing-safety-alert`, `xhs-pastel-card`, `dir-key-nav-minimal`) plus 7 scenario decks (`pitch-deck`, `product-launch`, `tech-sharing`, `weekly-report`, `xhs-post` 9-slide 3:4, `course-module`, `presenter-mode-reveal` 🎤 with 150–300 word speaker scripts on every slide).
- **36 page layouts**, **47 animations** (27 CSS + 20 canvas FX), **presenter mode with the `S` key**.

<p align="center">
  <a href="https://github.com/lewislulu/html-ppt-skill"><img src="https://raw.githubusercontent.com/lewislulu/html-ppt-skill/main/docs/readme/themes.png" width="720" alt="html-ppt-skill — 8 of 36 themes"/></a>
  <br><sub>8 of 36 themes.</sub>
</p>

---

#### 8. [zarazhangrui/beautiful-html-templates](https://github.com/zarazhangrui/beautiful-html-templates) · ⭐ 4,914

> A library of HTML slide templates designed so any coding agent can pick the right one and produce a beautiful deck on the user's behalf, automatically.

<p align="center">
  <a href="https://github.com/zarazhangrui/beautiful-html-templates"><img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/soft-editorial-4.png" width="720" alt="soft editorial template"/></a>
  <br><sub>Soft Editorial — one of 32 templates, each with cover · mid-deck · later variants.</sub>
</p>

Sibling repo to `frontend-slides` — pure templates, no skill logic. 32 templates, 3 slides each (cover · mid-deck · later) to give an agent a sense of how each visual system handles different layout duties before committing.

Also listed under [Templates](#templates) below.

---

#### 9. [stackblitz/bolt-slides](https://github.com/stackblitz/bolt-slides) · ⭐ 1,152

> Use any agent to create stunning, interactive presentations.

<p align="center">
  <a href="https://github.com/stackblitz/bolt-slides"><img src="https://raw.githubusercontent.com/stackblitz/bolt-slides/main/.github/assets/demo.gif" width="720" alt="Bolt Slides — from one prompt to a finished interactive deck"/></a>
  <br><sub>Above: one prompt in Bolt → a finished interactive deck (the README's own demo).</sub>
</p>

From StackBlitz, the team behind Bolt. Like open-slide, it is a React deck framework with a bundled agent skill rather than a single-file template: every slide is a plain React component, so a slide can fetch live data, mount a 3D scene or embed a working prototype. The skill ([`.bolt/skills/slides/SKILL.md`](https://github.com/stackblitz/bolt-slides/blob/main/.bolt/skills/slides/SKILL.md)) teaches Claude Code, Codex, Cursor or Bolt how to theme, compose and write the deck.

- **Component library** — `Cover`, `Agenda`, `Section`, `Split`, `Bento`, charts (bar · line · donut), `Table`, `StatGrid`, `Timeline`, `Comparison`, `CodeWindow`, `BrowserFrame`, `Pricing`, `Globe` and more, all responsive.
- **Presenting** — thumbnail sidebar, grid overview, click-builds (`<Build at={n}>`), content-anchored annotations, and a presenter mode synced to a second tab (timer, next-slide preview, editable notes).
- **Theming** from a single `tokens.css` block; nine theme directions are documented in the skill.

The deck is a web app (Vite build) shared as a link — there is no `.pptx` output. MIT.

---

### Tier A · Production-ready / 100–1000 stars

Mature, actively maintained skills with a clear style point of view. Best when you know roughly what you want — e.g. "I need a McKinsey-style consulting deck" — and want a skill that does *only* that, well.

---

#### 10. [mucsbr/ppt-agent-workflow-san](https://github.com/mucsbr/ppt-agent-workflow-san) · ⭐ 652

> 渐进交互式 PPT 生成 skill — progressive interactive PPT generation.

<p align="center">
  <a href="https://github.com/mucsbr/ppt-agent-workflow-san"><img src="https://raw.githubusercontent.com/mucsbr/ppt-agent-workflow-san/main/1.png" width="720" alt="ppt-workflow preview"/></a>
</p>

Two-stage workflow split across sub-repos:

- `ppt-workflow/` — generates PPT content plans and exports HTML or PNG previews.
- `html-slide-to-pptx/` — converts structured HTML slides into editable PPTX.

Notable for treating the HTML→PPTX export problem as a first-class concern, not an afterthought.

---

#### 11. [archlizheng/frontend-slides-editable](https://github.com/archlizheng/frontend-slides-editable) · ⭐ 547

> Editable HTML presentation skill for Codex/Claude Code with drag-resize editing, slide reordering, local save/export, and PPTX-to-web conversion.

<p align="center">
  <a href="https://github.com/archlizheng/frontend-slides-editable"><img src="https://raw.githubusercontent.com/archlizheng/frontend-slides-editable/main/docs/preset-previews/bold-signal-cover.png" width="260" alt="Bold Signal"/>&nbsp;<img src="https://raw.githubusercontent.com/archlizheng/frontend-slides-editable/main/docs/preset-previews/electric-studio-cover.png" width="260" alt="Electric Studio"/>&nbsp;<img src="https://raw.githubusercontent.com/archlizheng/frontend-slides-editable/main/docs/preset-previews/neon-cyber-cover.png" width="260" alt="Neon Cyber"/></a>
  <br><sub>Three preset covers — Bold Signal · Electric Studio · Neon Cyber.</sub>
</p>

Editable fork of `zarazhangrui/frontend-slides`. Keeps the upstream style discovery, viewport discipline, and PPT conversion, then adds a full in-browser editing runtime: drag objects, resize blocks, edit text, reorder slides, save locally, export a clean standalone HTML.

> Real decks should still implement each preset's signature layout from `STYLE_PRESETS.md`. Edit mode is an add-on, not permission to reuse a generic slide prototype for every aesthetic.

---

#### 12. [likaku/Mck-ppt-design-skill](https://github.com/likaku/Mck-ppt-design-skill) · ⭐ 328

> Consulting firm–style PowerPoint design system for AI agents. 70 layout patterns, flat design, python-pptx. 麦麸风格 PPT 设计系统。

<p align="center">
  <a href="https://github.com/likaku/Mck-ppt-design-skill"><img src="https://github.com/user-attachments/assets/075ec46d-dd73-4454-92d0-84184b78d276" width="380" alt="Mck cover slide"/>&nbsp;<img src="https://github.com/user-attachments/assets/3b25f071-8a81-48e3-a62b-9d9be9026f2e" width="380" alt="Mck content slide"/></a>
</p>

AI-native PowerPoint design system — 67 layouts · Harness Engineering · BLOCK_ARC charts · QA pipeline · Python runtime. The most opinionated McKinsey/BCG-style skill in the list; outputs lean PPTX rather than HTML, useful when the audience expects a `.pptx` file but you want consulting-grade typography.

---

#### 13. [vigorX777/ppt-svg-generator](https://github.com/vigorX777/ppt-svg-generator) · ⭐ 262

> Skill that converts Markdown into HTML/PDF presentations with multiple preset styles.

<p align="center">
  <a href="https://github.com/vigorX777/ppt-svg-generator"><img src="https://github.com/user-attachments/assets/2454e688-d3b8-40a2-a3f8-893bbe5060ee" width="720" alt="ppt-svg-generator preview"/></a>
</p>

| Style | Character | Use case |
| --- | --- | --- |
| 极简主义 | Pure white, lots of whitespace, Klein-blue accents | Product launches, design sharing, TED talks |
| 商务咨询 | Deep blue, McKinsey-style, orange emphasis | Proposals, consulting reports, investor pitches |
| 科技暗黑 | Dark background, neon gradients, glassmorphism | Tech sharing, product demos, hackathons |
| 瑞士平面 | High contrast, Bauhaus, signal red | Creative pitches, brand showcases |
| 品牌蓝 | Blue-purple-cyan palette, modern professional | Corporate training, formal presentations |

---

#### 14. [Akxan/ppt-agent-skill](https://github.com/Akxan/ppt-agent-skill) · ⭐ 172

> World-class AI presentation generator · 26 styles · 18 charts · benchmarked against Linear / Anthropic / Stripe / Apple / NYT.

<p align="center">
  <a href="https://github.com/Akxan/ppt-agent-skill"><img src="https://raw.githubusercontent.com/Akxan/ppt-agent-skill/main/assets/hero-all.png" width="720" alt="Akxan hero — 26 styles"/></a>
</p>

Models a full agency workflow rather than "outline → template": research first, content drives layout, global style stays consistent, real data fills placeholders. Visual fidelity is benchmarked against actual production CSS of brands like Linear and Anthropic — not screenshots, the real implementations.

**Style families**

- 暗色专业 — 7 styles (`references/styles/dark.md`)
- 浅色高级 — 8 styles (`references/styles/light.md`)
- 活力鲜明 — 4 styles (`references/styles/vibrant.md`)
- 东方文化 — 3 styles (`references/styles/cultural.md`)
- 自然/复古 — 4 styles (`references/styles/natural.md`)

---

#### 15. [humantonylee/future-slide](https://github.com/humantonylee/future-slide) · ⭐ 152

> Reusable slide-generation skill for image-based and HTML-based AI workflows.

<p align="center">
  <a href="https://github.com/humantonylee/future-slide"><img src="https://raw.githubusercontent.com/humantonylee/future-slide/main/public/diagram/four-skill-flow.png" width="720" alt="future-slide-skill flow"/></a>
</p>

One of the few skills designed to switch cleanly between image-rendered slides (e.g. for social media carousels) and live HTML decks from the same content IR. (Formerly `bytonylee/future-slide-skill`.)

---

#### 16. [software-ai-life/Awesome-PPT-Design-Skills](https://github.com/software-ai-life/Awesome-PPT-Design-Skills) · ⭐ 130

> Agent-agnostic PPT design skills for generating polished PowerPoint decks with [ppt-master](https://github.com/hugohe3/ppt-master).

Meta-collection rather than a single skill. The author packages multiple distinct visual systems (`japanese-style-ppt-skill`, `soft-3d-clay-ppt-skill`, `futuristic-tech-editorial-ppt-skill`, `minimalist-luxury-branding-ppt-skill`, `modern-illustration-editorial-ppt-skill`, `japanese-hand-drawn-editorial-ppt-skill`) and ships them as a stable visual layer for whichever coding agent you happen to use (Codex, Claude Code, Cursor, OpenCode, OpenClaw, Hermes). Traditional Chinese decks are first-class.

Also listed under [Templates](#templates) below.

---

#### 17. [joeseesun/qiaomu-bento-ppt](https://github.com/joeseesun/qiaomu-bento-ppt) · ⭐ 127

> Turn source material into an editable, presentable, offline-ready bento deck — one self-contained HTML file.

<p align="center">
  <a href="https://github.com/joeseesun/qiaomu-bento-ppt"><img src="https://raw.githubusercontent.com/joeseesun/qiaomu-bento-ppt/main/docs/assets/qiaomu-bento-ppt-hero.png" width="720" alt="qiaomu-bento-ppt — a generated bento deck"/></a>
</p>

Builds decks in the [bento](https://github.com/nyblnet/bento) `.bento.html` format, where one file carries the document, the viewer and the editor — the recipient double-clicks it to present, edit and save, with no PowerPoint install or cloud login. The skill first settles audience, conclusion and narrative arc, then routes each piece of content to a fitting primitive: trends to charts, specs to tables, before/after to morphs, key numbers to count-ups.

- **Standalone** — a release-pinned bento shell and the official authoring references are bundled, so no bento checkout or network download is needed after install.
- **Deterministic build and validation** — scripts check document identity, structure and the shell, and write a validation report for every deck.
- **Edits existing decks** — can modify a `.bento.html` file while preserving its document id.

Install: `npx skills add joeseesun/qiaomu-bento-ppt`.

---

#### 18. [gongnyang/awesome-html-scrolline-deck](https://github.com/gongnyang/awesome-html-scrolline-deck) · ⭐ 102

> Scroll-driven presentation decks: one continuous timeline, beats that turn into the next, six concept packs and 80 moves.

<p align="center">
  <a href="https://github.com/gongnyang/awesome-html-scrolline-deck"><img src="https://raw.githubusercontent.com/gongnyang/awesome-html-scrolline-deck/main/docs/hero.png" width="720" alt="Scrolline decks — a time rail, a morphing chart and a zoom into a single bar"/></a>
</p>

Despite the name, this is a tool (Scrolline) with a Claude Code skill, not a list. You write a `deck.yaml`; every beat is laid on one paused GSAP timeline that the mouse wheel scrubs and presenter keys jump through, and the same timeline renders to MP4. Instead of cutting between slides, "link moves" carry an element (a bar, a dot, a date) from one beat into its place in the next.

- **Six concept packs** — `rail` (time rail), `data` (data journalism), `launch`, `zoom` (infinite drill-down), `canvas` (camera flythrough), `kinetic` (kinetic type) — each with its own camera axis, timing and signature moves.
- **CLI** to scaffold a deck from a concept, compute stops and timings, and export MP4.
- Requires Node.js 22+; the six example decks are in Korean. MIT.

---

#### 19. [borjaperfra/beatdeck](https://github.com/borjaperfra/beatdeck) · ⭐ 100

> Talks as beats, not slides: a fixed 1920×1080 React stage where one click is one beat. Offline, deterministic, presenter view, and a Claude Code skill.

<p align="center">
  <a href="https://github.com/borjaperfra/beatdeck"><img src="https://raw.githubusercontent.com/borjaperfra/beatdeck/main/docs/media/demo-state.jpg" width="720" alt="beatdeck demo — a state diagram built one node per click"/></a>
  <br><sub>A state diagram built one node per click (from the demo deck).</sub>
</p>

Built for speaker-led technical talks where a diagram grows, a counter runs or a terminal prints on cue. A talk is a few scenes, each a sequence of beats; the whole state is `{ scene, beat }`, so `#3.4` in the URL always renders the same frame whether you arrived going forward, going back or by refreshing.

- **One stage** — fixed 1920×1080, scaled with a black letterbox, so nothing reflows on the projector.
- **Offline by construction** — fonts, images and QR codes are bundled or computed locally; the build fails if anything references the network.
- **Built-in components** — `Reveal`, `CountUp`, `Typewriter`, `Terminal`, self-drawing `NodeBox` + `Arrow` diagrams, `Plot` charts, local `QR`.
- **Operator tools** — presenter window (current/next beat, notes, timer), overview, blackout; the bundled skill (`building-a-beatdeck`) writes the talk with you. MIT.

---

### Tier B · Emerging / specialized

Smaller star counts, but several of these are the *best* option for their niche — Huawei-style strategy decks, knowledge-retention teaching slides, anti-AI-slop design tokens, etc.

---

#### 20. [edu-ai-builders/visual-cognition-slides](https://github.com/edu-ai-builders/visual-cognition-slides) · ⭐ 89

> An HTML slide design skill grounded in cognitive science and instructional design. Outputs presentation decks optimized for knowledge retention.

Every decision — narrative structure, per-slide layout, animation choice — answers a single question: *what cognitive action does the audience need to perform here?*

**Best for**: teachers, researchers, PhD students, content creators (voice-over videos, knowledge channels), internal training and talks.
**Not for**: pure commercial decks (PowerPoint / Keynote ship faster), real-time collaborative editing (use Google Slides).

---

#### 21. [UniUni2000/slideblocks-skill](https://github.com/UniUni2000/slideblocks-skill) · ⭐ 81

> SlideBlocks agent skill for creating and improving Slidev presentations.

<p align="center">
  <a href="https://github.com/UniUni2000/slideblocks-skill"><img src="https://raw.githubusercontent.com/UniUni2000/slideblocks-skill/main/media/showcase.png" width="720" alt="16 SlideBlocks pages"/></a>
</p>

Builds on [Slidev](https://sli.dev): hand the agent your materials (e.g. *"turn this paper into a 15-minute research talk"*) and it writes the Slidev source, then gives you an `offline.html` to present from Chrome or Edge — fullscreen, presenter view, slide overview and annotation tools. Ordinary text can be double-clicked and edited in the browser and saved with ⌘/Ctrl + S; right-click exports offline HTML or PDF. No `.pptx` output; an agent with image-generation tools is recommended. MIT.

Install: `npx skills add UniUni2000/slideblocks-skill`.

---

#### 22. [Jane-xiaoer/paper-collage-ppt](https://github.com/Jane-xiaoer/paper-collage-ppt) · ⭐ 68

> An agent skill by Xiaoer (小耳) for creating expressive HTML presentation decks in multiple visual styles.

Started as a paper-cut collage style (小耳剪纸风) and now ships a small style gallery: 好奇果冻 3D (translucent jelly type and clay objects, Three.js), 顽趣实验室 3D (a playful lab with original monster characters) and 小耳几何风 (flat, interlocking geometric grids).

- **Paper-collage deck** — single-file HTML (keyboard / wheel / touch), 20 layout skeletons, and 14 art-history palettes (Matisse cut-outs, Mondrian, Bauhaus, Klein blue, Monet, Hokusai, Dunhuang murals…) that viewers can switch from an in-deck panel with an accent-hue slider.
- **Text stays real HTML**, so it never garbles; illustrations can optionally be generated with nano-banana.
- **Editable PPTX export** — scripts for the paper-collage and 3D styles keep real text boxes. MIT.

---

#### 23. [zuiho-kai/huawei-style-ppt-skill](https://github.com/zuiho-kai/huawei-style-ppt-skill) · ⭐ 66

> 华为风格 PPT Skill — high-density information PPT workflow.

<p align="center">
  <a href="https://github.com/zuiho-kai/huawei-style-ppt-skill"><img src="https://raw.githubusercontent.com/zuiho-kai/huawei-style-ppt-skill/master/examples/rd-quarterly/screenshots/01-cover.png" width="720" alt="Huawei-style demo — R&amp;D quarterly review cover"/></a>
</p>

End-to-end workflow specifically tuned for Huawei-style strategy pages, architecture overviews, data insights, and side-by-side solution comparisons — i.e. document-style high-density decks that are intentionally heavier than a typical slide.

---

#### 24. [arifszn/slide-wright](https://github.com/arifszn/slide-wright) · ⭐ 66

> Make a presentation with your coding agent. Preview two slides, approve, then build and export to PowerPoint or PDF.

<p align="center">
  <a href="https://github.com/arifszn/slide-wright"><img src="https://github.com/user-attachments/assets/3e496913-753c-4761-873c-b7f6618a0b93" width="720" alt="slide-wright"/></a>
</p>

A preview-first loop: from a topic, rough notes or an outline it generates a custom palette and typography plus a two-slide preview, and builds the full self-contained HTML deck only after you approve (or generates a fresh direction if you don't). Includes speaker view with notes, overview and blackout keys, and can deploy the deck to a live URL. PowerPoint export keeps text as editable text boxes with speaker notes, while shapes, charts and images are baked into each slide's background. Installs as a Claude Code plugin or into any `SKILL.md` agent. MIT.

---

#### 25. [WayneZhon/KingDee-PPT-Skill](https://github.com/WayneZhon/KingDee-PPT-Skill) · ⭐ 59

> 将文字、大纲、文档一键转换为金蝶官方风格 .pptx 或交互式 HTML 幻灯片。

Fully reproduces the 2026 official Kingdee International template design language. Dual-style system (Classic / Bento Motion), 29 layouts, 7 auto-detected thinking models, embedded official background and logo, zero-config.

---

#### 26. [kaisersong/slide-creator](https://github.com/kaisersong/slide-creator) · ⭐ 57

> A skill for Claude Code and OpenClaw that generates stunning, zero-dependency HTML presentations.

<p align="center">
  <a href="https://github.com/kaisersong/slide-creator"><img src="https://raw.githubusercontent.com/kaisersong/slide-creator/main/demos/screenshots/bold-signal.png" width="380" alt="Bold Signal demo"/>&nbsp;<img src="https://raw.githubusercontent.com/kaisersong/slide-creator/main/demos/screenshots/electric-studio.png" width="380" alt="Electric Studio demo"/></a>
</p>

- **IR-first workflow** — `--plan` distills `BRIEF.json`, `--generate` renders from the IR.
- **Two planning depths** — Auto for speed, Polish for narrative + visual locking.
- **Content Review System** — 16 checkpoints; `--review` for on-demand diagnosis; Polish auto-runs review; three rule types (hard / context-aware / advisory).
- **22 design presets** with named layout variations.
- **Content-type routing** — auto-suggests best style for pitch decks, dev tools, data reports.
- **Style discovery** — 3 visual previews before committing.
- **Inline SVG diagrams** — flowcharts, timelines, bar charts, comparison grids, org charts. No external libs.
- **"Blue Sky" starter template** so models never mis-implement the visual system.

---

#### 27. [codesstar/next-slide](https://github.com/codesstar/next-slide) · ⭐ 55

> 你的下个 slide，何必是 PPT — AI-powered HTML presentations. 26+ styles, zero dependencies, bilingual. Works with Claude Code & OpenClaw, Hermes Agent.

Each style is a complete design system: curated typography, color palette, layout patterns, signature animations, responsive breakpoints.

| Category | Count | Styles | Vibe |
| --- | --- | --- | --- |
| Dark | 11 | Keynote Noir, Bold Signal, Neon Cyber, Terminal Green, Midnight Corporate, Cinema Scope, Dark Botanical, Starfield, Dark Premium, Dark Cinema, Futuristic Blue | Conferences, launches, tech talks |
| Light | 11 | Swiss Modern, Paper & Ink, Notebook Tabs, Pastel Geometry, Morning Brief, Campus White, Soft Landing, Watercolor Wash, Korean Soft, Claymorphism 3D, Wabi-Sabi Zen | Academic, business, teaching |
| Editorial | 4 | Editorial Serif, Fashion Editorial, Newsprint Broadsheet, Vintage Editorial | Magazine layouts, thought leadership |
| Bold | 7 | Electric Studio, Creative Voltage, Split Pastel, Pop Art, Bold Typography, Neon Brutalism, Memphis Pop | Startups, creative pitches |
| Retro | 5 | Grainy Retro, Art Deco Gatsby, Risograph Overprint, Vintage Poster, Retro Arcade | Nostalgic, stylized |
| Artistic | 7 | Surrealism Gallery, Scrapbook Portfolio, Blue Collage, Pink Handwritten, Art Nouveau Botanical, Soft Dreamy, Terracotta Earth | Art, design, portfolio |
| Cultural | 8 | 东方墨韵, 和風, Gradient Dreams, Blueprint, Bauhaus Primary, Swiss Grid, Aurora Mesh, Chinese Ink Wash | Cultural events, themed talks |

---

#### 28. [RinDig/lecture-deck-skill](https://github.com/RinDig/lecture-deck-skill) · ⭐ 51

> Build animated, themed HTML lecture and workshop decks from a storyboard. A Claude skill plus a Python kit with three themes.

<p align="center">
  <a href="https://github.com/RinDig/lecture-deck-skill"><img src="https://raw.githubusercontent.com/RinDig/lecture-deck-skill/master/examples/demo/shots/readme-themes.png" width="720" alt="lecture-deck demo screens in three themes"/></a>
</p>

Designed for live teaching sessions (in a room or on Zoom) with breakouts and screen-share handoffs: one claim per screen, one picture that shows the mechanism, speaker notes that carry the depth, and a mode strip on every screen so the room always knows who has the screen. Each deck is one self-contained HTML file with keyboard navigation, notes panel, overview, blackout, print-to-handout and copy-to-clipboard prompts. Three themes ship (`eduba`, `slate`, `paper`) — a theme is one JSON file — and bundled scripts render a PNG per screen for checking. MIT.

---

#### 29. [patrick-fu/frontend-harness-slides](https://github.com/patrick-fu/frontend-harness-slides) · ⭐ 45

> Build slide decks as a harness-guarded engineering project — robust, maintainable, and hard to break. A step up from single-file HTML slides.

<p align="center">
  <a href="https://github.com/patrick-fu/frontend-harness-slides"><img src="https://raw.githubusercontent.com/patrick-fu/frontend-harness-slides-workbench/main/public/showcase/product-keynote.webp" width="720" alt="Minimal Product Keynote preset — hero frame"/></a>
  <br><sub>Minimal Product Keynote preset, from the project's style gallery.</sub>
</p>

For the phase after the first draft, when a growing deck starts breaking under edits. The skill has the agent treat the deck as a small, testable web app: stable scene and beat addresses, a registry tooling can enumerate, a fixed-ratio stage, a frozen mode for repeatable screenshots, event-isolated interactions, and smoke tests for missing content, overflow and navigation leaks. Style presets span six families (Minimal Keynote, Balanced Hybrid, Editorial & Print, Craft & Cultural Traditions, Contemporary Digital, Text Report). Ships as a live site, a PDF, or both. MIT.

Install: `npx skills add patrick-fu/frontend-harness-slides -g`.

---

#### 30. [FeeiCN/slide-writer](https://github.com/FeeiCN/slide-writer) · ⭐ 44

> A slide-writing skill that generates enterprise HTML presentations from ideas, outlines, documents, and speech drafts.

<p align="center">
  <a href="https://github.com/FeeiCN/slide-writer"><img src="https://raw.githubusercontent.com/FeeiCN/slide-writer/main/examples/slide-writer.png" width="720" alt="slide-writer example"/></a>
</p>

- **Any input → enterprise-grade deck** — sentence, outline, speech draft, notes, existing HTML.
- **14 brand themes, auto-detected** — Ant Group, Alibaba, Tencent, ByteDance and more. Mention the keyword, the right theme/logo/colors load automatically.
- **Single-file delivery** — one standalone HTML; CSS, JS, images all embedded. Opens in any browser.
- **Always up to date** — pulls latest themes, components, and generation rules on every run.

---

#### 31. [Phlegonlabs/Powerpoint-fancy-design](https://github.com/Phlegonlabs/Powerpoint-fancy-design) · ⭐ 42

> A presentation-design skill for Codex and Claude Code that turns page-structured Markdown into styled 1600x900 HTML slides, PNG renders, and exportable PPTX decks.

<p align="center">
  <a href="https://github.com/Phlegonlabs/Powerpoint-fancy-design"><img src="https://raw.githubusercontent.com/Phlegonlabs/Powerpoint-fancy-design/main/assets/style-preview-a.png" width="720" alt="Swiss International preview"/></a>
</p>

**Use it for**:

- Business and policy decks needing disciplined hierarchy and presentation-safe typography.
- Brand / culture / exhibition decks needing stronger visual direction than stock templates.
- Chinese and bilingual decks needing style-aware font pairing instead of generic fallbacks.
- Static HTML-to-PPT workflows where final visual fidelity matters more than editable PPT primitives.

---

#### 32. [nghiahsgs/skills-slides](https://github.com/nghiahsgs/skills-slides) · ⭐ 33

> 50,000+ unique HTML presentation designs. Zero dependencies. Anti-AI-slop. A Claude Code skill.

<p align="center">
  <a href="https://github.com/nghiahsgs/skills-slides"><img src="https://raw.githubusercontent.com/nghiahsgs/skills-slides/main/examples/screenshots/slide-06-features.png" width="720" alt="skills-slides features slide"/></a>
</p>

Fights AI-generated mediocrity with a **token-based design system** and a strict **anti-slop checklist** that catches generic patterns *before* the deck is delivered. Result: decks that look intentionally designed, not template-generated.

- **Aesthetics (50)** — `startup-pitch`, `neon-cyber`, `editorial-minimal`, `luxury-noir`, `consulting-swiss`, `vaporwave`, `terminal-hacker`, `ai-ml-showcase`, and more. Each defines compatible palettes, fonts, layouts, and signature effects.
- **Palettes (20)** — `midnight-aurora`, `crimson-signal`, `electric-indigo`, `rose-gold`, `arctic-frost`, `carbon-fiber`, etc. WCAG contrast ratios shipped for every palette.
- **Fonts (10)** — Display + body pairs from Google Fonts and Fontshare (`clash-satoshi`, `fraunces-worksans`, `syne-spacemono`, `bodoni-dmsans`).
- **Effects (30+)** — full CSS+JS snippets with performance impact tagged: `particle-bg`, `gradient-mesh`, `aurora-flow`, `grid-overlay`, `glassmorphism`, `noise-texture`, `magnetic-cursor`.

---

#### 33. [jxshow/Jingge-PPT-skill](https://github.com/jxshow/Jingge-PPT-skill) · ⭐ 25

> 鲸格PPT：17种视觉风格，可编辑HTML演示文稿、汇报、讲堂与发布模板。 — 17 visual styles; editable HTML decks and templates for reports, lectures and launches.

<p align="center">
  <a href="https://github.com/jxshow/Jingge-PPT-skill"><img src="https://raw.githubusercontent.com/jxshow/Jingge-PPT-skill/main/examples/style-atlas/%E9%B2%B8%E6%A0%BCPPT-%E5%85%A8%E9%83%A8%E9%A3%8E%E6%A0%BC%E6%80%BB%E8%A7%88.png" width="720" alt="Jingge PPT — overview of all 17 styles"/></a>
</p>

鲸格 PPT — a Codex Skill for generating high-quality browser-native presentations. Static HTML/CSS/JS output with a complete pipeline: content IR, theme system, full deck templates, single-page layouts, animation runtime, presenter mode, editable mode, gesture controls, export helpers. (Formerly `xhshow2025/-PPT-sense-deck-skill-`.)

**Distinctive themes**

- `apple-bento-glass` — AI / product strategy / new-category launches.
- `executive-clean` — board reports, strategy updates, investor updates, weekly reports.
- `semantic-dark` — tech sharing, architecture walkthroughs, AI systems, developer demos.
- `xhs-editorial` — Xiaohongshu image-text, social carousels, consumer education.
- `cyber-neon` — Demo Day, RGB hardware, cyberpunk launches.
- `warm-paper` — courses, lecture notes, stories, cultural themes.
- `nordic-childrens-picture-book` — Nordic children's-book nostalgia and humor.
- 史诗级 — historical cultural narratives, 昭君出塞, Chinese cinematic feel.
- `neon-noir-city` — cyberpunk city, AI future life, 2098-style narratives.

---

## Export to editable PowerPoint (PPTX)

HTML is the better authoring format, but many decks end up with someone who only works in PowerPoint — a client who wants to change the numbers, an event that only accepts `.pptx` uploads, a team whose templates live in Office. "Export to PPTX" can mean two quite different files, so check which one a tool produces:

- **Image-per-slide PPTX** — each slide is a screenshot placed on a PowerPoint page. Pixel-exact and fine for projecting, but nothing is editable.
- **Editable PPTX** — text becomes native text boxes and simple shapes become PowerPoint shapes; effects PowerPoint can't express (complex gradients, filters, WebGL, 3D) are flattened into pictures. Expect some cleanup of fonts and line breaks.

**Built into skills on this list**

- [dashi-ppt-skill](#5-chuspeeismdashi-ppt-skill---10258) — one-click editable PPTX from its in-browser editor.
- [huashu-design](#3-alchaincyfhuashu-design---28440) — HTML deck plus an editable PPTX with text frames preserved.
- [ppt-agent-workflow-san](#10-mucsbrppt-agent-workflow-san---652) — a separate `html-slide-to-pptx/` stage for structured HTML slides.
- [paper-collage-ppt](#22-jane-xiaoerpaper-collage-ppt---68) — per-style export scripts that keep real text boxes.
- [slide-wright](#24-arifsznslide-wright---66) — editable text and speaker notes; shapes, charts and images baked into each slide's background.

**Converting an existing HTML deck**

| Project | Stars | How it works |
| --- | --- | --- |
| [atharva9167j/dom-to-pptx](https://github.com/atharva9167j/dom-to-pptx) | 389 | Client-side JavaScript library built on PptxGenJS: walks the DOM, reads computed styles and maps elements to native shapes and text boxes; v2 adds speaker notes and PowerPoint animations / transitions. Also installs as an agent skill (`npx dom-to-pptx-skills`). MIT. |
| [Hasasasa/html-to-editable-pptx](https://github.com/Hasasasa/html-to-editable-pptx) | 94 | Agent skill + Python CLI for single-file decks (beautiful-html-templates, guizang-ppt-skill, Reveal.js, hand-written). Native text boxes, on-demand font subsetting, local snapshots for CSS effects PowerPoint can't express, and HTML-vs-PPTX side-by-side audit images. MIT. |
| [wangzan101/html-to-ppt-pdf](https://github.com/wangzan101/html-to-ppt-pdf) | 40 | Skill for guizang-ppt-skill decks: Playwright captures each page at 1920×1080 into a PDF and an image-per-slide PPTX. Not editable, but visually exact. MIT. |
| [Design-Arena/html-to-pptx](https://github.com/Design-Arena/html-to-pptx) | 25 | Python CLI / library (`pip install html-to-pptx`) that measures every DOM element in headless Chromium and maps it to a PPTX shape. MIT. |

Anthropic's [`pptx` skill](https://github.com/anthropics/skills/tree/main/skills/pptx) (in `anthropics/skills`) used to ship an `html2pptx` workflow — author slides as HTML, convert them with a bundled script. That workflow was removed in February 2026; the current skill has the agent write [PptxGenJS](https://github.com/gitbrent/PptxGenJS) scripts directly, plus validation and thumbnail tools. It fits when you are happy for the agent to rebuild the deck natively rather than convert your HTML. The skill is source-available under a proprietary license.

**Rasterize, then rebuild**

When a deck relies on things a DOM-to-shape converter can't follow (WebGL backgrounds, canvas, 3D), export it to PDF or slide screenshots first — most skills above can export PDF, or print from Chrome — then use a tool that reconstructs editable text boxes and shapes from the images:

- [ningzimu/image-to-editable-ppt-skill](https://github.com/ningzimu/image-to-editable-ppt-skill) · 3,217 ⭐ — open-source Codex skill that rebuilds slide images, PDFs and image-based PPTX page by page: OCR'd text becomes native text boxes, simple geometry becomes shapes, complex visuals stay as separate image assets. Runs on your own Codex quota (its README recommends ChatGPT Pro for multi-page decks). MIT.
- [ToseaAI/editable-pptx-skill](https://github.com/ToseaAI/editable-pptx-skill) — A Claude Code / Codex skill that sends PDFs, slide screenshots or images to the [Reslide](https://reslide.tosea.ai) API and returns an editable PPTX. Billed per page; new accounts get 10 free pages. *(Made by Tosea.ai, which maintains this list.)*
- Tosea.ai web tools, free with sign-in (a shared allowance of 5 pages a month on the free plan): [PDF to PPT](https://tosea.ai/free-tools/pdf-to-ppt) · [Image to editable PPT](https://tosea.ai/free-tools/image-to-editable-ppt) · [NotebookLM slides to PowerPoint](https://tosea.ai/free-tools/notebooklm-slides-to-powerpoint). Image conversions on the free plan carry a small watermark.

---

## Templates

Hand-crafted HTML template libraries — drop them into a project, point your agent at the folder, get a deck.

---

#### T1. [zarazhangrui/beautiful-html-templates](https://github.com/zarazhangrui/beautiful-html-templates) · ⭐ 4,914

> A library of HTML slide templates designed so any coding agent can pick the right one and produce a beautiful deck on the user's behalf, automatically.

<p align="center">
  <a href="https://github.com/zarazhangrui/beautiful-html-templates"><img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/vellum-1.png" width="260" alt="Vellum cover"/>&nbsp;<img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/stencil-tablet-1.png" width="260" alt="Stencil Tablet cover"/>&nbsp;<img src="https://raw.githubusercontent.com/zarazhangrui/beautiful-html-templates/main/screenshots/neo-grid-bold-1.png" width="260" alt="Neo Grid Bold cover"/></a>
  <br><sub>Three of 32 templates — Vellum · Stencil Tablet · Neo Grid Bold.</sub>
</p>

**32 templates**, three slides per template (cover · mid-deck · later) to show how each visual system handles different layout duties. The de-facto reference template library for the Claude Code skill ecosystem — many skills above will pull from or reference these templates directly.

---

#### T2. [software-ai-life/Awesome-PPT-Design-Skills](https://github.com/software-ai-life/Awesome-PPT-Design-Skills) · ⭐ 130

> Agent-agnostic PPT design skills, distributed as a library of style packs.

Acts as a multi-style template library when you don't want to commit to one aesthetic:

- **japanese-style-ppt-skill** — 日本風格高端編輯簡報 with two house styles:
  - *Washi Paper & Soft Glow* — 和紙感米白背景, 柔和微光與低彩度色系, 細灰線、靛藍克制點綴, 大量留白但有溫度.
  - *Japanese Lifestyle Editorial* — 純白背景, 焦橙與深炭灰, 高端生活雜誌式排版, 非對稱壓邊圖片與結構化 grid.
- **soft-3d-clay-ppt-skill** — Claymorphism. 暖米色 `#FDF5E6`, 鼠尾草綠 `#B2AC88`, 莫蘭迪粉 `#DBADAD`, 柔霧感幾何形狀.
- **futuristic-tech-editorial-ppt-skill** — Futuristic tech editorial. 純白 `#FFFFFF`, 電光藍 `#2F6BFF`, 石墨灰 `#2B2B2B`, 細線 grid, 資料感模組, 平面銳利.
- **minimalist-luxury-branding-ppt-skill** — High-end brand proposal. 暖米色 `#F5EFE6`, 柔棕色 `#A68A64`, 深灰文字 `#3A3A3A`, 襯線標題 + 無襯線內文, 精品感節奏.
- **modern-illustration-editorial-ppt-skill** — Modern illustration editorial. 柔米色 `#F7F3EE`, 霧藍 `#A7C7E7`, 灰橘 `#E8A87C`, 炭灰 `#2F2F2F`, 柔和向量插畫.
- **japanese-hand-drawn-editorial-ppt-skill** — Japanese hand-drawn editorial. 暖白紙感 `#F8F6F2`, 墨黑線條 `#2B2B2B`, 柔灰 `#BDBDBD`, 低彩靛藍 `#6C7A89`, 鉛筆/墨線插畫 + 淡水彩.

---

## Contributing

PRs welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). The bar:

1. Repo must be public, MIT/Apache/CC-style licensed, and contain real working code (a skill manifest or a template directory — not just a README).
2. Output must be HTML-first (PPTX export is fine as long as HTML is the source of truth).
3. Star count is checked at PR merge time and used to place the entry in the right tier.
4. If your project has a demo GIF, banner, or screenshot grid in its README, include a `<p align="center"><img></p>` block linking to the raw asset URL — see existing entries for the pattern.

If you find a broken link, a stale star count, or a project we missed, [open an issue](https://github.com/ToseaAI/awesome-html-slide-skills/issues/new).

---

## License

Curated content (this README, the structure, the descriptive text) is licensed under [CC BY 4.0](LICENSE). Each linked project retains its own license — check the linked repos before reuse.

Inline preview images are hot-linked from each project's own GitHub repository (under `raw.githubusercontent.com` or `github.com/user-attachments`). They remain the copyright of their respective authors and are shown here as fair-use thumbnails to help readers identify each project at a glance. If you are the author of a project featured here and would like a preview removed or swapped, [open an issue](https://github.com/ToseaAI/awesome-html-slide-skills/issues/new) and we'll fix it immediately.

---

<p align="center">
  Maintained by <a href="https://tosea.ai"><b>Tosea.ai</b></a> · <a href="https://tosea.ai/slide-skills">Browse on the web</a> · <a href="https://github.com/ToseaAI/awesome-gpt-image-2-prompts">Also see: awesome-gpt-image-2-prompts</a>
</p>
