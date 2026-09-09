# English
# 👋 Hi there, I'm Wang Jun 
## 🚀 About Me
- 🤖 AI Engineering Lead | LLM Agent Runtime & Harness Engineering | Context / Cost Engineering | AI-Native Dev Workflows | Blockchain Architect
- 🏢 Currently Technical Lead in the AI department of a top-3 global crypto exchange (2025–present): built the production agent stack behind its consumer AI investment assistant, now bringing coding agents into the company's engineering workflow
- 🎓 Graduated from a top 985 university in China with a master's degree in Computer Science
  - Perfect score in Math for the National College Entrance Examination (Gaokao)
  - 2nd place in the provincial Physics Olympiad
  - Excellent Graduation Thesis Award for both bachelor's and master's degrees
- 🏆 Multiple Champion of Industry Algorithm Competitions
  - Anomaly detection algorithm models outperformed teams from the Chinese Academy of Sciences and top companies in the industry
- 💼 9+ years in AI / big data, 5+ years leading engineering teams; shipped AI products from 0 to 1 across telecom, fintech risk control, AIOps, AIGC and blockchain
- 💻 Proficient in blockchain architecture design and development for DeFi, NFT, and GameFi applications

## 🔥 Recent Work: LLM Agent Systems (2025–present)
- **Agent runtime from scratch**: Replaced a third-party low-code stack (Dify) with a self-built agent runtime — single-pass plan + tool-call loop, vector-based intent routing, multi-level caching, long-term memory, parallel tool calls and an MCP-compatible tool layer. First-token latency 30s+ → 3–6s (simple queries 1–2s), LLM call volume halved, and a 4.5 vs. 3.7 competitor-average score in a four-dimension benchmark (accuracy / intent / safety / UX). The same runtime now powers six product surfaces; onboarding a new one dropped from ~2 weeks to 2–3 days
- **Harness engineering**: Independently built an autonomous task agent (~19k lines of Python, 725 automated tests) as the capability donor for the next-gen architecture — Anthropic-spec-aligned SSE streaming, AG-UI protocol, human-in-the-loop approval, three-layer context compression, long-running task harness with a self-verification loop, extended thinking, code sandbox, sub-agent parallelism and full-trace observability. Audited the production system against a six-component harness framework and authored the five-tier architecture roadmap
- **Cost & context engineering**: Profiled real token traffic (over 99% of input was system prompt + tool schemas), then drove a prompt-caching strategy end to end — KV-cache hit rate 27% → 75%, system prompt tokens −34.5%, and a standardized caching + Langfuse tracing pipeline rolled out across three service repos
- **LLM as a CI reviewer**: Designed a two-gate quality system for LLM-application code — semgrep rules for cache / cost / trace hygiene, plus an 8-dimension semantic review with adversarial verification and bounded evidence gathering. Zero false positives on both a hand-built dimension baseline and a regression set of real historical production bugs; adopted across four core production repos
- **Coding agents in the dev workflow**: Leading the AI side of the company's AI-native R&D platform — migrated its assistant onto the in-house agent runtime in 27 days (0 → production, 767 automated tests), mechanized write-confirmation and idempotency for every agent write action, and shipped an MCP access center so Claude Code / Codex / Cursor connect to the platform directly under each engineer's own permissions
- **Enablement**: Delivered a company-wide livestream on how LLMs actually work (and why they fail); authored the team's AI-collaboration engineering standard, later encoded into the automated CI checks above

## 🎉 Honors & Awards
- 2023 - AIGC digital human project led by me was reported and recommended by People's Daily
- 2021 - Led the team to win the XX Bank Intelligent O&M project and received the Excellent Project Award
- 2020 - Talent with the highest overall score in the company's talent review
- 2020 - Responsible for the CASE that won 1st place in multiple intelligent O&M pre-sales POCs
- 2019 - 1st place in the AIIA Cup AI Competition by China AI Industry Development Alliance
- 2017 - 1st and 2nd place in the Zhejiang Mobile Big Data Competition
- 2016 - 1st place in the Tianjin New Talent category of the 1st China Unicom IT Strategic Talent Selection
- 2015 - 1st place in the 1st Tianjin Unicom Information Technology Business Support Skills Competition

## 🛠️ Featured Projects
- **AIGC Projects**: Offline deployment and training of large models, text-to-text, text-to-image, talking digital humans, live streaming digital humans, customer service digital humans, and more
- **AI in Blockchain**: Practical applications of artificial intelligence technology in blockchain
- **Intelligent Insight Product**: Root cause localization product based on metric systems, successfully implemented in the data center of XX Bank (one of the Big Four banks in China)
- **Electricity Theft Detection**: Low-voltage electricity theft user identification for the State Grid Corporation of China, outperforming the National Electric Power Research Institute
- **Credit Precise Marketing**: Optimization of credit marketing response models, steadily improving model performance and generating nearly 10 million revenue for the company
- **Financial Risk Control**: Optimization of credit risk scoring card models

# 中文
# 👋 你好,我是王钧 
## 🚀 关于我
- 🤖 AI 工程负责人 | LLM Agent 运行时与 Harness 工程 | 上下文 / 成本工程 | AI 原生研发流程 | 区块链架构师
- 🏢 现任全球 TOP3 加密货币交易所 AI 部门技术负责人(2025 至今):从零搭建了其 C 端 AI 投资助手背后的生产级 Agent 技术栈,目前在推动编码智能体进入公司研发工作流
- 🎓 毕业于中国顶尖985院校,获得计算机科学硕士学位
  - 高考数学满分
  - 物理奥赛省级第二名
  - 本科和硕士均获优秀毕业论文奖
- 🏆 多次获得业内算法竞赛冠军
  - 异常检测算法模型优于中科院和业内顶尖公司团队
- 💼 9 年以上 AI / 大数据经验,5 年以上技术团队管理经验;在电信、金融风控、AIOps、AIGC、区块链多个领域主导 AI 产品从 0 到 1 落地
- 💻 精通区块链架构设计和开发,涉及DeFi、NFT和GameFi应用

## 🔥 近期工作:LLM Agent 系统(2025 至今)
- **从零自研 Agent 运行时**:用自研运行时替换第三方低代码平台(Dify)——单次调用完成规划与工具调用的 Agent Loop、向量意图路由、多级缓存、长期记忆、多工具并行调用、兼容 MCP 的工具层。首字响应 30s+ → 3–6s(简单查询 1–2s),LLM 调用次数减半,四维度(准确性 / 意图理解 / 安全性 / 体验)竞品评测 4.5 分 vs 竞品均分 3.7 分。同一套运行时已支撑六个产品场景,新场景接入周期从约 2 周缩短到 2–3 天
- **Harness 工程**:独立完成一个自主任务型 Agent(约 1.9 万行 Python、725 个自动化测试),作为下一代架构的能力供体——对齐 Anthropic 规范的 SSE 流式协议、AG-UI 协议、人工审批(HITL)、三层上下文压缩、带自验证闭环的长时任务 Harness、Extended Thinking、代码沙箱、子 Agent 并行、全链路 trace。以六部件 Harness 框架审计线上系统,产出五层架构升级路线图
- **成本与上下文工程**:实测真实 token 结构(输入中 99% 以上是 system prompt 与工具说明),据此推动 prompt caching 从方案到落地——KV-cache 命中率 27% → 75%,system prompt token 减少 34.5%,并沉淀出缓存 + Langfuse 链路追踪的标准流程,在三个服务仓统一落地
- **LLM 进 CI 做评审员**:为 LLM 应用代码设计"双闸"质量体系——semgrep 规则覆盖缓存 / 成本 / trace 三类工程卫生,语义闸做 8 维度评审,内置反方核实与有界取证。手写维度基线与真实历史生产缺陷回归集均零误报,已接入四个核心生产代码仓
- **编码智能体进入研发工作流**:负责公司 AI 原生产研平台的 AI 侧——27 天内将其助手迁移到自研 Agent 运行时(0 → 生产,767 个自动化测试),为所有 Agent 写操作机制化了写前确认与幂等,并上线 MCP 接入中心,使 Claude Code / Codex / Cursor 能在工程师各自权限内直连平台
- **团队赋能**:面向全公司直播讲解大模型的底层原理与失效方式;撰写团队《AI 协作约束规范》,其中的规则后续被固化为上述 CI 自动检查项

## 🎉 荣誉与奖项
- 2023 - 我主导的AIGC数字人项目获得人民日报报道和推荐
- 2021 - 带领团队赢得XX银行智能运维项目,并获得优秀项目奖
- 2020 - 在公司人才评估中获得最高综合分
- 2020 - 负责的方案在多个智能运维售前POC中获得第一名
- 2019 - 获得中国人工智能产业发展联盟AIIA杯人工智能竞赛第一名 
- 2017 - 浙江移动大数据竞赛第一名和第二名
- 2016 - 首届中国联通IT战略人才选拔天津新锐人才类第一名
- 2015 - 首届天津联通信息技术业务支撑技能大赛第一名

## 🛠️ 主要项目
- **AIGC项目**: 大模型离线部署和训练,文本到文本、文本到图像、会说话的数字人、直播数字人、客服数字人等
- **区块链中的AI**: 人工智能技术在区块链中的实际应用
- **智能洞察产品**: 基于指标体系的根因定位产品,成功在XX银行(四大行之一)数据中心落地
- **窃电检测**: 为国家电网公司进行低压窃电用户识别,效果超过国家电力研究院
- **信贷精准营销**: 信贷营销响应模型优化,稳步提升模型性能,为公司创造近千万收入
- **金融风控**: 信贷风险评分卡模型优化
