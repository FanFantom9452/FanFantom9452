<div align="right">

[English](./README.md) · [**繁體中文**](./README.zh-TW.md)

</div>

# Hi, 我是 FanFantom 👋

[![YouTube](https://img.shields.io/badge/YouTube-@FanFantom-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@FanFantom/)

我喜歡做一些奇奇怪怪的工具。像是一些公司業務的作業流程，其實很多都是重複複製貼上，再加入一些自己簡單的判斷，我這個人偏好——能用工具加速就做工具，能整段自動化處理就走自動化。
對於製作通用功能，我會選擇多花時間把客戶真正卡住的地方弄清楚，再做一個能直接命中問題的客製化平台、工具、機器人等。
在一場會議裡，我會用 PM 的角度看業務想要解決的點，還有對方經理或是老闆希望解決的事情，再用工程師的角度下去思考解決方法，對我來說，商業面優先考量，其次才是技術面。

下班的空閒時間，我也會在 YouTube 上分享 Minecraft 內容（資料包介紹、實況、地圖製作） —— [**@FanFantom**](https://www.youtube.com/@FanFantom/)。

由於我的工作和案子大多數受 NDA 限制，底下的描述會刻意寫得籠統一點。

---

## 🧰 技術棧

**程式語言**

[![Languages](https://skillicons.dev/icons?i=py,cs,java,ts,js,cpp,c,html,css,bash,powershell,latex)](https://skillicons.dev)

**框架與函式庫**

[![Frameworks](https://skillicons.dev/icons?i=fastapi,flask,react,vite,svelte,electron,tailwind,nodejs,bun)](https://skillicons.dev)

**平台與基礎建設**

[![Infra](https://skillicons.dev/icons?i=docker,nginx,postgres,sqlite,linux,ubuntu,windows,raspberrypi,unity,arduino)](https://skillicons.dev)

![Linux Mint](https://img.shields.io/badge/Linux_Mint-87CF3E?style=flat&logo=linuxmint&logoColor=white)
![Wine](https://img.shields.io/badge/Wine-722F37?style=flat&logo=wine&logoColor=white)

**工具**

[![Tools](https://skillicons.dev/icons?i=git,github,vscode)](https://skillicons.dev)

**ML / NLP / 其他**

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

## 🚀 做過的東西

### 私有專案（NDA 內容，故意寫得籠統）

- **B2B SaaS／ERP 類平台** —— 模組化 FastAPI + React 19 monorepo，
  多租戶資料隔離，通用核心之上用 feature flag 疊各家客戶的專屬擴充，
  涵蓋主檔、BOM 階層與規格文件查詢。
- **跨系統整合機器人** —— 用 Playwright 排程登入廠商上游平台
  （含 SSO 防護），把資料對到客戶端資料庫，比對差異後逐筆新增、
  更新、刪除，附重試與限速控制，整包跑在 Docker 裡。
- **受規範零件目錄的 RAG 搜尋** —— Ollama + FAISS + BM25 八階段
  pipeline，agent orchestration 全用 asyncio + ReAct 手刻，沒掛
  LangGraph 之類的框架。
- **AI 對話機器人** —— 走 ReAct + Plan-and-Execute 雙層推理，有一套
  仿 Claude Code 的 Skill 系統，會在背景從對話自動抽出 Knowledge
  Graph，PostgreSQL + pgvector 一條龍存 skill／memory／KG／embedding。
- **桌面媒體工具** —— Electron + Svelte 寫的桌面 App，做影片壓縮、
  剪輯，外加一塊原生 sidecar binary 跑會議 STT 轉錄。
- **網頁工具** —— 一個自架的短期檔案中繼站（適合臨時丟檔），加上
  一套多人即時協作的 LaTeX 編輯器。

### 公開專案

- **`dfu_pseudo_hsi`** —— 手機優先的臨床影像研究原型，主題是糖尿病足
  風險篩檢；Flask + Tailwind + Docker，附自簽 HTTPS 讓手機瀏覽器能
  順利存取 camera API。
- **Minecraft 資料包** —— `CreeperWarsII`(開發中)、`DeathRun-Datapack`(開發中)、
  `UHCMeetUp`(已完成)，另有社群工具 `MinecraftParticleGenerator`(已完成)，提供
  Python 與 Unity GUI 兩種實作。介紹與遊玩影片放在
  [YouTube 頻道](https://www.youtube.com/@FanFantom/)。
- **`FantomBuzzWire`** —— 高中職專題：電子「電流急急棒」反應遊戲
  機台（Arduino、C++）。

---

## 🏗️ 專案領域

我做的東西多半服務於傳統與受規範產業的 line-of-business 場景 ——
這些行業的規格散在一堆舊文件裡，把流程跑順、做對，本身就是產品的
核心價值。

- **客製化自動工作流工具**
- **B2B 貿易／供應鏈 ERP**
- **軌道產業工作流工具**
- **國防／受規範採購支援**
- **語音與媒體工具**

---

## 🤖 我如何和 Claude Code 共同協作

底下是我平常開發的時候喜歡用的清單，也推薦給大家做使用，
最常用的應該是caveman / superpower 這兩個插件，其他則是有機會才用到。

### 第三方 Marketplace

| Marketplace | 來源 |
| --- | --- |
| caveman | <https://github.com/JuliusBrussee/caveman> |
| karpathy-skills | <https://github.com/multica-ai/andrej-karpathy-skills> |
| huggingface-skills | <https://github.com/huggingface/skills> |

### ⭐ 常用主力

幾乎每個 session 都會用到的：

- **`superpowers`** —— brainstorming、TDD、debugging、verification-before-completion。
- **`caveman`** —— Token 壓縮溝通模式。
- **`commit-commands`** —— commit／push／PR 引導流程。
- **`context7`** —— 即時函式庫文件查詢。
- **`pr-review-toolkit`** —— 多 agent 完整 PR review。
- **`frontend-design`** —— 高品質 UI 開發。

### 📌 推薦

頻率較低但價值高的：

- **`karpathy-guidelines`** —— LLM 寫 code 常見錯誤的行為護欄。
- **`skill-creator`** —— 撰寫／維護自製 skill。
- **`claude-md-management`** —— 替 CLAUDE.md 做體檢與微調。
- **`code-review`** —— 聚焦單一 PR 的 review。
- **`agent-sdk-dev`** —— 建立／驗證 Claude Agent SDK app。
- **`feature-dev`** —— 引導式功能實作流程。
- **`code-simplifier`** —— 重構近期改動的程式碼，行為不變。

### 🧰 額外安裝

領域類／情境類：

- **`huggingface-skills`** *(官方 bundle)* —— 包下面五個 HF skill。
- **`hugging-face-dataset-viewer`** · **`hugging-face-model-trainer`** · **`hugging-face-vision-trainer`** · **`hugging-face-evaluation`** · **`transformers-js`** —— HF 工作流工具集。
- **`github`** —— GitHub CLI / API 整合。
- **`playwright`** —— 瀏覽器自動化測試與驗證。
- **`greptile`** —— 語意化程式碼搜尋。
- **`explanatory-output-style`** —— 教學模式輸出風格。
- **`security-guidance`** —— 安全 review 提示。

### 🔌 Language Server

- **`typescript-lsp`** · **`pyright-lsp`** · **`rust-analyzer-lsp`**

*最後檢視：2026-05-19。*

---

## 📊 GitHub Stats

![FanFantom9452's GitHub stats](https://github-readme-stats.vercel.app/api?username=FanFantom9452&show_icons=true&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=FanFantom9452&layout=compact&hide_border=true&langs_count=8)
