# Easy AI Skills: AI Skills & Agent Skills 精選導航

[繁体中文](README.md) · [English](README.en.md)

### 這個項目是什麼？
本項目收集、整理並精選了 GitHub 上真實可落地、針對具體業務場景的 **AI Skills**（涵蓋 Claude 外掛、Cursor 規則、MCP 技能節點等形態）。

### 這個項目有什麼用？
當前 GitHub 上有大量零散的 AI 項目，但大多數偏向底層技術演示。本項目嚴格從「實際業務痛點」出發，專為出海營銷、電商選品、內容分發等場景，過濾出真正能給 AI 直接裝備、拿來幹活的**實用 Skills**。
極大地**降低你的篩選成本**，明確告訴你在每個具體的營運節點：**該給你的 AI 裝備什麼 Skill，以及怎麼用**。

### 🎯 適合人群
跨境電商賣家、海外社媒矩陣營運者、獨立站站長，以及希望利用 AI IDE（如 Cursor / Windsurf / Claude Code）構建個人自動化工作流的超級個體。

---

## ⚙️ 運行準備

- **安裝指令**：已寫入了下列表格內容
- **基礎環境**：視具體項目要求，可能需預裝 Python、Node.js 或配置好相應的 AI 編輯器。
- **API 金鑰**：調用模型或外部平台接口時，需自備相應平台的 API Key。
- **網絡環境**：部分涉及海外社媒抓取、跨國電商數據採集的 Skill 對網絡有要求，建議配置代理 IP。
- **代理資源**： [ipcook](https://www.ipcook.com/user/register?ref=7ZNPKW) 高匿住宅代理以防數據請求被攔截。
- 🎁 **領取折扣碼**：【**WELCOME20**】**8折優惠**（新人註冊後7日內用）
 [點擊註冊購買時輸入折扣碼ipcook](https://www.ipcook.com/user/register?ref=7ZNPKW)
- 這家的住宅代理IP價格都很實惠，可以先屯一波！
<a href="https://www.ipcook.com/user/register?ref=7ZNPKW" target="_blank"><img width="1760" height="586" alt="36bd8dfc49097ceb23878ff2e3b5a0e1" src="https://github.com/user-attachments/assets/a0729d28-02c8-4667-8898-477a0b340cb2" />

---

##  內容產出（腳本、影片、文章） Skills

### 影片腳本、文章、爆款文案與SEO博客

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [NotebookLM Skill](https://github.com/claude-world/notebooklm-skill) | 結合 NotebookLM 做深度資料研究，自動生成長文和腳本，是長篇資料提煉和「洗稿降重」的絕佳利器。 | 需 Claude Code | `/skill add notebooklm-skill` |
| [Claude Blog](https://github.com/AgriciDaniel/claude-blog) | 30 個寫作 Skill 覆蓋博客全流程，優化 Google SEO 排名，提供極專業的獨立站 SEO 優化建議。 | 需 Node.js 環境 | `/skill add claude-blog` |
| [Drama Skills](https://github.com/worldwonderer/drama-skills) | AI 短劇/漫劇創作全套流水線，涵蓋劇本、分鏡與提示詞生成。 | 需 Claude/Codex | `/skill add drama-skills` |
| [Writing Style Skill](https://github.com/jzOcb/writing-style-skill) | 內置自動學習功能，可精準模仿特定作者的寫作風格。 | 需提供寫作樣本 | `/skill add writing-style-skill` |
| [Better Documents](https://github.com/anildash/better-documents) | 應用溝通最佳實踐來大幅改進技術文檔與 SOP 的質素。 | 零門檻 | `/skill add better-documents` |

### AI 畫圖、電商配圖與一鍵去背

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [Generative Media Skills](https://github.com/SamurAIGPT/Generative-Media-Skills) | 跨平台的高質素圖像、影片和音頻生成集成庫。 | 支援多個 CLI | `npm install -g generative-media-skills` |
| [Banana Claude](https://github.com/AgriciDaniel/banana-claude) | 由 Gemini 驅動的 AI 圖像生成工具，出圖極快且免費額度友好，非常適合大批量快速配圖。 | 需 Gemini API | `/skill add banana-claude` |
| [Nano Banana 2 Skill](https://github.com/kingbootoshi/nano-banana-2-skill) | 專注 AI 圖像生成 CLI，支援綠幕透明度處理和風格轉移。 | 支援 Claude Code | `/skill add nano-banana-2-skill` |
| [Ecommerce Visual Copywriting](https://github.com/feichanggege/ecommerce-visual-copywriting-skill) | 針對電商產品圖自動生成視覺文案與排版，一鍵搞定高轉化主圖，幫助小賣家省下美工費。 | 需圖片素材 | `/skill add ecommerce-visual-copywriting-skill` |

### 自動剪影片、長影片切片與加字幕

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | 用 Remotion 配合 152 個鏡頭配方批量生成電影級產品影片。 | 需 Node.js 環境 | `npm install video-shotcraft` |
| [Clipify](https://github.com/louisedesadeleer/clipify) | 自動提取長影片高光時刻，重構為 9:16 豎屏並加面部追蹤字幕，堪稱 YouTube Shorts 和 TikTok 切片號的印鈔機。 | 支援 Claude Code | `/skill add clipify` |
| [Video Recap Skills](https://github.com/worldwonderer/video-recap-skills) | 將任意長影片自動剪輯並生成中文解說，支援無縫導出至剪映。 | 支援 Claude Code | `/skill add video-recap-skills` |
| [BaoCut](https://github.com/JimLiu/baocut) | 自動化 macOS 本地剪輯應用，一鍵完成轉錄、翻譯和粗剪。 | 需 macOS | [查閱項目主頁](https://github.com/JimLiu/baocut) |
| [Claude Shorts](https://github.com/AgriciDaniel/claude-shorts) | 長影片轉短影片工具，內置 AI 片段自動評分系統。 | 支援 Claude Code | `/skill add claude-shorts` |

### 網頁排版與圖文格式轉換

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [HTML Anything](https://github.com/nexu-io/html-anything) | 涵蓋海報、社媒卡片等 9 種排版場景，一鍵生成並發布。 | 零門檻 | `/skill add html-anything` |
| [Huashu MD HTML](https://github.com/alchaincyf/huashu-md-html) | Markdown 與 HTML 雙向轉換流水線，內置 4 套「反 AI 味」主題，做公眾號和博客排版可告別格式錯亂。 | 支援 Claude Code | `/skill add huashu-md-html` |

---

## 📱 社交媒體全渠道營運與自動發布 Skills

### 矩陣號自動發帖與帳號代營運

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [Social AI Team](https://github.com/stevenflanagan1/social-ai-team) | 建立品牌專屬聲音檔案，生成內容日曆並自動化管理整個社媒審批流。 | 需配置品牌資料 | `/skill add social-ai-team` |
| [Claude Skill Social Post](https://github.com/Hao0321/claude-skill-social-post) | 深度學習帳號語氣並分發到 FB/IG/X 等多平台，模仿效果極其驚艷，自動化程度極高。 | 支援 Claude Code | `/skill add claude-skill-social-post` |
| [Claude Ads](https://github.com/AgriciDaniel/claude-ads) | 覆蓋 12 個核心平台的付費媒體投放審計與報表自動生成。 | 需海外代理 | `/skill add claude-ads` |
| [Agent Skill Creator](https://github.com/FrancyJGLisboa/agent-skill-creator) | 將任何標準工作流轉換為可重用的 AI Agent Skills。 | 需懂工作流設計 | `/skill add agent-skill-creator` |

### TikTok 找對標帳號、扒爆款與抓評論

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [TikHub API Skill](https://github.com/liangdabiao/tikhub_api_skill) | 搜索 TikTok 熱門趨勢，定向獲取影片詳情和海量評論，是尋找對標帳號和挖掘買家痛點的極強抓取工具。 | 需海外代理 | `/skill add tikhub_api_skill` |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | 官方 Playwright 瀏覽器自動化 MCP 伺服器，通殺所有網頁數據採集。 | 需海外代理 | `npm install @playwright/mcp` |

### X (Twitter) 自動推文與熱點監控

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [X Article Publisher Skill](https://github.com/wshuyi/x-article-publisher-skill) | 將本地 Markdown 文章一鍵自動化推送到 X (Twitter) Articles。 | 支援 Claude Code | `/skill add x-article-publisher-skill` |
| [X Research Skill](https://github.com/rohunvora/x-research-skill) | 針對 X 平台的深度研究 Agent：推文線程跟蹤與來源簡報生成。 | 需海外代理 | `/skill add x-research-skill` |
| [GitHub MCP Server](https://github.com/github/github-mcp-server) | GitHub 官方 MCP 伺服器，用於自動化監控競品代碼庫和開發動態。 | 需 GitHub API | `npm install @github/mcp-server` |

### LinkedIn 領英 B2B 拓客與互動

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [LinkedIn Skills](https://github.com/sergebulaev/linkedin-skills) | 自動化撰寫 LinkedIn 帖子、自動評論互動和 Feed 流深度分析。 | 支援 Claude Code | `/skill add linkedin-skills` |
| [Activepieces](https://github.com/activepieces/activepieces) | AI 工作流自動化平台，包含 400+ 節點，完美支援領英自動化，猶如開源版 Zapier，適合搭建極度複雜的自動化流。 | 需海外代理 | `docker run -p 3000:3000 activepieces/activepieces` |

### 📸 小紅書 / Instagram 視覺內容營運

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [Bazi Ziwei Skill](https://github.com/dzcmemory-web/bazi-ziwei-skill) | AI 八字 + 紫微斗數命理綜合印證，是玄學引流號批量製造爆款算命貼的必備神器。 | 需一定命理常識 | `/skill add bazi-ziwei-skill` |
| [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) | 最大的 MCP 伺服器聚合資源庫，內含大量社媒自動化數據提取腳本。 | 視具體項目而定 | [查閱項目主頁](https://github.com/punkpeye/awesome-mcp-servers) |

### ▶️ YouTube 營運與數據分析

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [YouTube Transcript Extractor](https://github.com/jdepoix/youtube-transcript-api) | 支援多語言的 YouTube 影片無字幕提取 API，準確率極高。 | 需海外代理 | `pip install youtube-transcript-api` |
| [Headroom](https://github.com/headroomlabs-ai/headroom) | 處理超長 YouTube 影片前自動壓縮文本，大幅降低大模型的 Token 消耗，長期調用能省下不少 API 費用。 | 需配置代理 | `npm install headroom` |

---

## 🛒 跨境電商選品與競品爬取 Skills

### 亞馬遜 (Amazon) 查競品與 Listing 優化

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [Amazon Sorftime Research MCP](https://github.com/liangdabiao/amazon-sorftime-research-MCP-skill) | 亞馬遜 Listing 全維度穿透分析，含競品與差評抓取，提供 Sorftime 官方級別的數據顆粒度，亞馬遜賣家直接閉眼入。 | 需海外代理 | `/skill add amazon-sorftime-research-MCP-skill` |
| [Amazon Skills](https://github.com/nexscope-ai/Amazon-Skills) | 亞馬遜專屬關鍵詞研究、競品分析與 Listing 審計自動化工具。 | 需海外代理 | `/skill add Amazon-Skills` |
| [Codebase Memory MCP](https://github.com/DeusData/codebase-memory-mcp) | 高性能代碼智能 MCP 伺服器，可用於逆向分析競品電商網站代碼。 | 需技術分析基礎 | `npm install codebase-memory-mcp` |

### 🗣️ 買家評論抓取與用戶分析
| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [Private GPT](https://github.com/zylon-ai/private-gpt) | 本地化部署的 AI API 層，可安全處理海量電商評論並做情感分析。 | 需本地算力部署 | `docker run -p 8000:8000 private-gpt` |

### 📈 獨立站 SEO 分析與網站數據爬取

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [AI Marketing Suite](https://github.com/zubair-trabzada/ai-marketing-claude) | 包含 15 個營銷 Skill，自動出具競品情報和「客戶就緒」級分析報告。 | 支援 Claude Code | `/skill add ai-marketing-claude` |
| [DataForSEO Claude](https://github.com/zubair-trabzada/dataforseo-claude) | 網站關鍵詞排名跟蹤、反向連結審計與競品 SEO 深度剖析，數據維度全面且專業，獨立站 SEO 操盤手必備。 | 需海外代理 | `/skill add dataforseo-claude` |
| [FastMCP](https://github.com/PrefectHQ/fastmcp) | 極速構建 MCP 伺服器的 Python 框架，用於捏制自定義的商業監控看板。 | 需 Python 基礎 | `pip install fastmcp` |

### 🛍️ Shopify / Dropshipping 一件代發自動化

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [Ecommerce Visual Copywriting](https://github.com/feichanggege/ecommerce-visual-copywriting-skill) | 電商視覺文案 SOP，一鍵生成高轉化產品主圖與描述。 | 需圖片素材 | `/skill add ecommerce-visual-copywriting-skill` |
| [DBX Database Client](https://github.com/t8y2/dbx) | 內置 AI 的輕量級資料庫客戶端，用自然語言直接管理電商後台海量訂單數據。 | 需資料庫權限 | `npm install -g dbx` |

### 🚢 跨境物流與供應鏈管理

| 項目名稱 | 功能說明 | 運行門檻 | 安裝指令 / 連結 |
| :--- | :--- | :--- | :--- |
| [Logistics Tracker MCP](https://github.com/modelcontextprotocol/python-sdk) | 利用官方 SDK 構建的物流追蹤器，支援多國跨境快遞軌跡監控。 | 需海外代理 | `pip install mcp` |
| [Activepieces](https://github.com/activepieces/activepieces) | 用 400+ 節點打通 ERP、物流商與店鋪後台，搭建全鏈路供應鏈監控流。 | 需海外代理 | `docker run -p 3000:3000 activepieces/activepieces` |

---

## 📌 收錄原則與免責聲明

- **收錄原則**：近期活躍更新、擁有清晰文檔、能直接解決真實業務痛點。
- **推薦提報**：歡迎透過 Issue 或 Pull Request 推薦優秀項目，格式要求請查閱 [CONTRIBUTING.md](CONTRIBUTING.md)。
- **安全提醒**：第三方 Skill 工具可能涉及訪問網絡或讀取本地文件，安裝前請仔細閱讀 [SECURITY.md](SECURITY.md) 注意數據安全。
- **免責聲明**：本項目不對第三方工具提供官方背書。進行數據採集時，請務必遵守適用法律與各平台規則。
