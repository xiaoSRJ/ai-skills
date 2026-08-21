# Easy AI Skills：AI Skills / Agent Skills 中文精选导航

[简体中文](README.md) · [English](README.en.md)

**关键词 / Keywords**：AI Skills, AI Agent, Claude Code, Cursor, Codex, MCP Server, TikTok 运营, 社媒自动化, 电商选品, 内容创作, 视频制作, 海外营销, 数据采集, 工作流自动化, Agent Skills

> 精选 GitHub 上真正活跃的 AI Skills、Agent Skills、Claude Code Skills、Cursor Skills 和 MCP Server，按真实业务工作流分类，用中文说明每个项目能解决什么问题、怎么上手。

## 这个仓库能帮你解决什么问题

GitHub 上的 AI Skills 越来越多，但质量参差不齐。对大多数用户来说，真正困难的不是"找到一个链接"，而是判断：

- 这个 Skill 到底能做什么，适合我的业务场景吗；
- 是否需要 API Key、依赖环境或编程基础；
- 原项目是否还在维护，值不值得花时间尝试。

**Easy AI Skills** 只做筛选、分类、中文说明和导航，不复制或重新发布第三方 Skill 源代码。所有项目的代码、文档、商标和许可证仍归原作者所有。

我们按**真实业务工作流**组织内容，每个工作流拆解为具体节点，告诉你在这个节点可以用什么 Skill 来增强 AI 的能力。

## 前期准备

不同 Skill 对运行环境的要求差异很大，安装前建议先确认：

- **运行环境**：部分 Skill 需要 Python、Node.js 或特定版本的运行时；
- **API Key**：涉及外部服务（AI 模型、数据平台、社媒 API）的 Skill 通常需要配置密钥；
- **浏览器 / 登录状态**：浏览器自动化类 Skill 需要已登录的浏览器会话；
- **网络环境**：部分项目（如海外社媒抓取、跨国电商数据采集）对网络环境有要求，建议配置如 [ipcook](https://www.ipcook.com/user/register?ref=7ZNPKW) 等高匿住宅代理以防封禁。

## 如何使用这份导航

1. 按你的业务场景选择下方对应的工作流；
2. 在表格中找到当前卡住的业务节点；
3. 点击项目名称进入原仓库，阅读最新 README 和安装说明；
4. 只安装当前真正需要的 Skill，避免一次加载过多规则；
5. 遇到脚本、API Key、浏览器登录或文件权限时，先确认风险再执行。

---

## 第一部分：AI 写作与图文创作工作流

> 选题与热搜挖掘 → 大纲与长文深度生成 → 提示词与配图生成 → 自动化排版

| 业务节点 | 项目名称 | 解决什么业务问题 | 上手要求 | 安装说明 / 命令 |
|---|---|---|---|---|
| 选题与热搜挖掘 | [NotebookLM Skill](https://github.com/claude-world/notebooklm-skill) | 让 NotebookLM 做资料研究，Claude 基于研究结果写内容；适合需要先吃透资料再动笔的深度内容场景 | 中：需要配置 NotebookLM 和 Claude Code | 查阅项目主页 |
| 选题与热搜挖掘 | [Marketing Skills](https://github.com/coreyhaines31/marketingskills) | 做 SEO 审计、站点结构规划和程序化 SEO；适合需要系统性做内容营销和流量增长的团队 | 低到中：方法型 Skill，但需提供真实产品和数据 | 查阅项目主页 |
| 大纲与长文深度生成 | [Claude Blog](https://github.com/AgriciDaniel/claude-blog) | 30 个子 Skill 组成的博客写作套件，从大纲到成稿全流程；双优化 Google 排名和 AI 引用 | 中：需要配置博客环境和 SEO 工具 | 查阅项目主页 |
| 大纲与长文深度生成 | [Research Paper Writing Skills](https://github.com/Master-cai/Research-Paper-Writing-Skills) | 覆盖文献阅读、论文写作到科学计算的完整学术写作工作流；适合科研人员和深度报告撰写 | 中：支持 Codex、Claude Code、Gemini | 查阅项目主页 |
| 提示词与配图生成 | [Generative Media Skills](https://github.com/SamurAIGPT/Generative-Media-Skills) | 高质量图像、视频和音频生成；适合需要为文章配图、生成封面或制作多媒体内容的场景 | 中到高：需要配置生成媒体工具链 | 查阅项目主页 |
| 提示词与配图生成 | [Banana Claude](https://github.com/AgriciDaniel/banana-claude) | AI 图像生成 Skill，由 Gemini 驱动；适合快速生成文章配图和视觉素材 | 中：需要配置 Gemini API | 查阅项目主页 |
| 自动化排版 | [HTML Anything](https://github.com/nexu-io/html-anything) | 75 个 Skill 覆盖杂志、海报、社媒卡片等 9 种排版场景；一键发布到微信/X/知乎/HTML/PNG | 低：零 API Key，支持 Claude Code/Cursor/Codex 等 | 查阅项目主页 |
| 自动化排版 | [Huashu MD HTML](https://github.com/alchaincyf/huashu-md-html) | Markdown 与 HTML 双向转换流水线；4 套反 AI 味主题，适合公众号和博客排版 | 低：支持 Claude Code | 查阅项目主页 |

## 第二部分：视频制作与处理工作流

> 爆款脚本提取与仿写 → 视频素材分析与理解 → 音视频处理与字幕自动化 → 封面图生成

| 业务节点 | 项目名称 | 解决什么业务问题 | 上手要求 | 安装说明 / 命令 |
|---|---|---|---|---|
| 爆款脚本提取与仿写 | [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | 152 个镜头配方卡和 209 个动画预览，用 Remotion 生成电影级产品视频；适合需要批量生产高质量视频的团队 | 高：需要 Node.js、React 和 Remotion 环境 | 查阅项目主页 |
| 爆款脚本提取与仿写 | [Drama Skills](https://github.com/worldwonderer/drama-skills) | 从创意到分镜的完整短剧创作链路；生成剧本、人物设定、图片/视频提示词；适合短剧和漫剧创作 | 中到高：适配 Claude Code 与 Codex | 查阅项目主页 |
| 视频素材分析与理解 | [Clipify](https://github.com/louisedesadeleer/clipify) | 自动找到长视频中的有趣时刻，剪辑并重新构图到 9:16 竖屏，带面部追踪和字幕；适合把长视频切成社媒短片 | 中：支持 Claude Code | 查阅项目主页 |
| 视频素材分析与理解 | [Video Recap Skills](https://github.com/worldwonderer/video-recap-skills) | 把任何视频剪辑成中文解说视频，支持剪映导出；适合做影视解说和内容二次创作 | 中：支持 Claude Code | 查阅项目主页 |
| 音视频处理与字幕自动化 | [BaoCut](https://github.com/JimLiu/baocut) | 驱动 BaoCut macOS 应用完成转录、字幕、翻译和剪辑；适合需要自动化处理音视频素材的 Mac 用户 | 中：需要 macOS 和 BaoCut 应用 | 查阅项目主页 |
| 音视频处理与字幕自动化 | [Claude Shorts](https://github.com/AgriciDaniel/claude-shorts) | 长视频转短视频，Remotion 渲染动画字幕、AI 片段评分；适合播客切片和课程精华提取 | 中：支持 Claude Code | 查阅项目主页 |
| 封面图生成 | [Generative Media Skills](https://github.com/SamurAIGPT/Generative-Media-Skills) | 多模态生成媒体 Skill，支持图像、视频和音频生成；适合批量生成视频封面和缩略图 | 中到高：需要配置生成媒体工具链 | 查阅项目主页 |
| 封面图生成 | [Nano Banana 2 Skill](https://github.com/kingbootoshi/nano-banana-2-skill) | AI 图像生成，支持绿幕透明度、参考图像和风格转移；适合快速生成视频封面和产品图 | 中：支持 Claude Code 插件 | 查阅项目主页 |

## 第三部分：TikTok 与海外社媒运营工作流

> 对标账号数据抓取 → 批量生成/润色贴文 → 自动发布与平台分发 → 评论区自动交互

| 业务节点 | 项目名称 | 解决什么业务问题 | 上手要求 | 安装说明 / 命令 |
|---|---|---|---|---|
| 对标账号数据抓取 | [TikHub API Skill](https://github.com/liangdabiao/tikhub_api_skill) | 搜索 TikTok/抖音热门视频、话题和趋势；获取视频详情、评论和用户数据；适合做竞品分析和爆款研究 | 中：需要 TikHub API Key；需海外网络/代理 | 查阅项目主页 |
| 对标账号数据抓取 | [X Research Skill](https://github.com/rohunvora/x-research-skill) | X/Twitter 深度研究：Agentic 搜索、线程跟踪、来源简报；适合做海外舆情监控和竞品跟踪 | 中：支持 Claude Code 和 OpenClaw；需海外网络/代理 | 查阅项目主页 |
| 批量生成/润色贴文 | [Social AI Team](https://github.com/stevenflanagan1/social-ai-team) | 建立品牌声音，生成内容日历、captions 和创意方向；适合需要统一管理多平台社媒内容的团队 | 中：需要配置品牌资料和内容方向 | 查阅项目主页 |
| 批量生成/润色贴文 | [Claude Skill Social Post](https://github.com/Hao0321/claude-skill-social-post) | 学习你的社媒语气，自动生成并发布到 FB/IG/Threads/X；带 14 天内容日历；适合个人品牌和小团队 | 中：支持 Claude Code | 查阅项目主页 |
| 自动发布与平台分发 | [Claude Ads](https://github.com/AgriciDaniel/claude-ads) | 覆盖 12 个广告平台的付费媒体运营（Google、Meta、TikTok、Amazon 等）；审计、评分和报告；适合投放团队 | 中到高：需要配置各平台 API；需海外网络/代理 | 查阅项目主页 |
| 自动发布与平台分发 | [X Article Publisher Skill](https://github.com/wshuyi/x-article-publisher-skill) | 把 Markdown 文章直接发布到 X (Twitter) Articles；适合需要把长文同步到 X 的创作者 | 低：支持 Claude Code | 查阅项目主页 |
| 评论区自动交互 | [LinkedIn Skills](https://github.com/sergebulaev/linkedin-skills) | 11 个 Skill 覆盖 LinkedIn 帖子写作、评论互动和 feed 分析；适合做 B2B 社媒运营和职场内容 | 中：支持 Claude Code 和 Codex | 查阅项目主页 |

## 第四部分：电商选品与竞品调研工作流

> 跨平台商品价格与销量监控 → 评论批量抓取与情感分析 → 市场趋势总结与报表生成

| 业务节点 | 项目名称 | 解决什么业务问题 | 上手要求 | 安装说明 / 命令 |
|---|---|---|---|---|
| 跨平台商品价格与销量监控 | [Amazon Sorftime Research MCP Skill](https://github.com/liangdabiao/amazon-sorftime-research-MCP-skill) | 亚马逊 Listing 全维度分析：全品类分析、关键词分析、差评分析、市场调研；适合亚马逊卖家做选品调研 | 中：需要配置亚马逊 API 和 MCP；需海外网络/代理 | 查阅项目主页 |
| 跨平台商品价格与销量监控 | [Amazon Skills](https://github.com/nexscope-ai/Amazon-Skills) | 关键词研究、竞品分析、Listing 审计；适合亚马逊卖家优化产品页面和跟踪竞品 | 中：支持 OpenClaw、Claude Code、Cursor 等；需海外网络/代理 | 查阅项目主页 |
| 评论批量抓取与情感分析 | [Amazon Sorftime Research MCP Skill](https://github.com/liangdabiao/amazon-sorftime-research-MCP-skill) | 差评分析和市场调研；从用户评论中提炼产品改进方向和卖点 | 中：需要配置亚马逊 API 和 MCP；需海外网络/代理 | 查阅项目主页 |
| 市场趋势总结与报表生成 | [AI Marketing Suite](https://github.com/zubair-trabzada/ai-marketing-claude) | 15 个营销 Skill：网站审计、文案生成、广告活动、竞争情报和客户就绪的 PDF 报告；适合营销团队出方案 | 中：支持 Claude Code | 查阅项目主页 |
| 市场趋势总结与报表生成 | [DataForSEO Claude](https://github.com/zubair-trabzada/dataforseo-claude) | 关键词研究、排名跟踪、反向链接审计、竞品分析和 PDF 报告；适合 SEO 团队和代理商 | 中：需要 DataForSEO API Key；需海外网络/代理 | 查阅项目主页 |

---

## 收录原则

本项目优先收录：

- **真正活跃**：近期有代码提交，不是停更半年以上的"死项目"；
- **质量可靠**：有清晰的文档和明确的使用场景；
- **来源明确**：原作者和原仓库地址清楚，不收录来路不明的项目；
- **实用导向**：能解决真实业务问题，不只是一个模糊的提示词。

## 推荐新项目

欢迎通过 Issue 或 Pull Request 推荐。请提供项目地址、具体用途、适合人群、上手要求和已知限制。格式见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 安全提醒

第三方 Skill 和 Agent 工具可能执行脚本、访问网络、读取本地文件、使用 API Key 或浏览器登录状态。安装前请查看 [SECURITY.md](SECURITY.md)，并以原仓库最新说明为准。

## 免责声明

- 本仓库不是所收录项目的官方仓库，也不代表与作者存在合作或背书关系；
- 项目功能、依赖、维护状态和安装方式可能随时变化；
- 使用浏览器自动化、数据采集和外部 API 时，请遵守适用法律、平台规则和数据保护要求；
- 推荐度不代表功能承诺、安全认证或适合所有用户。

## License

本仓库原创的分类、中文介绍和导航文字采用 [MIT License](LICENSE)。第三方项目仍受各自许可证约束。
