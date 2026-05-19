<div align="right">

[**English**](./README.md) · [繁體中文](./README.zh-TW.md)

</div>

# Hi, I'm FanFantom 👋

[![YouTube](https://img.shields.io/badge/YouTube-@FanFantom-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@FanFantom/)

I like building slightly odd tools. A lot of real business workflows are
just repetitive copy-paste with a thin layer of human judgement on top —
so my default move is: speed it up with a tool if I can, or pull the
whole step out of the loop with automation if I can do that instead.

When it comes to building generic features, I'd rather spend the extra
time figuring out where the customer is *actually* stuck, then ship a
custom platform, tool, or bot that hits exactly that spot.

In a meeting I switch between two lenses — the PM lens, for what the
business is trying to solve and what the manager or boss really wants
out of it, and the engineer lens, for how to actually pull it off.
The business side comes first for me; the tech side is there to serve it.

Off the clock I also post Minecraft content on YouTube (datapack
walkthroughs, gameplay, map-making) — [**@FanFantom**](https://www.youtube.com/@FanFantom/).

Most of my work and client projects sit under NDA, so the descriptions
below stay deliberately broad.

---

## 🧰 Tech Stack

**Languages**

[![Languages](https://skillicons.dev/icons?i=py,cs,java,ts,js,cpp,c,html,css,bash,powershell,latex)](https://skillicons.dev)

**Frameworks & Libraries**

[![Frameworks](https://skillicons.dev/icons?i=fastapi,flask,react,vite,svelte,electron,tailwind,nodejs,bun)](https://skillicons.dev)

**Platforms & Infrastructure**

[![Infra](https://skillicons.dev/icons?i=docker,nginx,postgres,sqlite,linux,ubuntu,windows,raspberrypi,unity,arduino)](https://skillicons.dev)

![Linux Mint](https://img.shields.io/badge/Linux_Mint-87CF3E?style=flat&logo=linuxmint&logoColor=white)
![Wine](https://img.shields.io/badge/Wine-722F37?style=flat&logo=wine&logoColor=white)

**Tools**

[![Tools](https://skillicons.dev/icons?i=git,github,vscode)](https://skillicons.dev)

**ML / NLP / Misc**

![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FFD21E?style=flat)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat&logo=postgresql&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Discord.py](https://img.shields.io/badge/Discord-py-5865F2?style=flat&logo=discord&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-005571?style=flat)
![BM25](https://img.shields.io/badge/BM25-grey?style=flat)
![RAG](https://img.shields.io/badge/RAG-orange?style=flat)
![Win32 native](https://img.shields.io/badge/Win32_native-0078D6?style=flat&logo=windows)

---

## 🚀 What I've Built

### Private work (descriptions kept deliberately broad)

- **B2B SaaS / ERP-style platforms** — modular FastAPI + React 19 monorepos,
  multi-tenant data isolation, feature-flag gated client extensions, master
  data + BOM hierarchy + spec retrieval.
- **Cross-system integration robots** — Playwright-driven scheduled sync
  between vendor portals (incl. SSO-protected ones) and customer
  databases, with row-level diff / insert / update / delete and retry
  pacing, fully Dockerised.
- **RAG search over regulated parts catalogs** — Ollama + FAISS + BM25
  pipeline, hand-rolled agent orchestration (asyncio + ReAct).
- **AI-powered chat bots** — ReAct + Plan-and-Execute reasoning, a
  Claude-Code-style Skill system, conversational Knowledge-Graph extraction,
  PostgreSQL + pgvector storage.
- **Desktop media tooling** — Electron + Svelte apps for video compression,
  editing, and meeting-STT transcription, with native sidecar binaries.
- **Web utilities** — a self-hosted file-relay service for short-lived
  shares, and a multi-user real-time collaborative LaTeX editor.

### Public

- **`dfu_pseudo_hsi`** — mobile-first clinical-imaging research prototype
  for diabetic-foot risk screening; Flask + Tailwind + Docker with
  self-signed HTTPS so phone browsers can access the camera API.
- **Minecraft datapacks** — `CreeperWarsII` *(in development)*,
  `DeathRun-Datapack` *(in development)*, `UHCMeetUp` *(shipped)*, plus a
  community `MinecraftParticleGenerator` tool *(shipped)* with both
  Python and Unity GUI implementations. Walkthroughs and gameplay on the
  [YouTube channel](https://www.youtube.com/@FanFantom/).
- **`FantomBuzzWire`** — high-school senior project: an electronic
  buzz-wire reaction-game arcade machine (Arduino, C++).

---

## 🏗️ Project Domains

I build line-of-business systems for regulated and traditional industries —
domains where the spec lives in legacy documents and the workflow is the
product.

- **Custom workflow-automation tooling**
- **B2B trading / supply-chain ERP**
- **Rail-industry workflow tooling**
- **Defense / regulated procurement support**
- **Speech & media tooling**

---

## 🤖 How I Collaborate With Claude Code

Below is the plugin set I personally lean on day to day — also a
reasonable starter list if you're picking your own. The two I touch
most are **caveman** and **superpowers**; the rest come out when the
situation calls for them.

### Third-Party Marketplaces

| Marketplace | Source |
| --- | --- |
| caveman | <https://github.com/JuliusBrussee/caveman> |
| karpathy-skills | <https://github.com/multica-ai/andrej-karpathy-skills> |
| huggingface-skills | <https://github.com/huggingface/skills> |

### ⭐ Daily drivers

Fire on almost every session:

- **`superpowers`** — brainstorming, TDD, debugging, verification-before-completion.
- **`caveman`** — token-compressed communication mode.
- **`commit-commands`** — guided commit / push / PR flow.
- **`context7`** — live library docs lookup.
- **`pr-review-toolkit`** — comprehensive multi-agent PR review.
- **`frontend-design`** — production-grade UI work.

### 📌 Recommended

Lower-frequency but high-value:

- **`karpathy-guidelines`** — behavioural guard-rails for LLM coding mistakes.
- **`skill-creator`** — author / maintain custom skills.
- **`claude-md-management`** — keep CLAUDE.md files healthy.
- **`code-review`** — focused single-PR review.
- **`agent-sdk-dev`** — scaffold and validate Claude Agent SDK apps.
- **`feature-dev`** — guided feature implementation flow.
- **`code-simplifier`** — refactor recently-touched code without changing behaviour.

### 🧰 Also installed

Domain / situational:

- **`huggingface-skills`** *(official bundle)* — wraps the five HF skills below.
- **`hugging-face-dataset-viewer`** · **`hugging-face-model-trainer`** · **`hugging-face-vision-trainer`** · **`hugging-face-evaluation`** · **`transformers-js`** — HF workflow toolkits.
- **`github`** — GitHub CLI/API integration.
- **`playwright`** — browser automation for testing & verification.
- **`greptile`** — semantic code search.
- **`explanatory-output-style`** — educational-mode output styling.
- **`security-guidance`** — security review prompts.

### 🔌 Language servers

- **`typescript-lsp`** · **`pyright-lsp`** · **`rust-analyzer-lsp`**

*Last reviewed: 2026-05-19.*

---

## 📊 GitHub Stats

![FanFantom9452's GitHub stats](https://github-readme-stats.vercel.app/api?username=FanFantom9452&show_icons=true&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=FanFantom9452&layout=compact&hide_border=true&langs_count=8)
