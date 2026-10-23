### 刘显中 · AI 应用开发

做 LLM 应用与 Agent 工程：工具调用、工作流编排、向量检索。六个项目全部自研，能跑、有 README。

**AI Agent（MCP / LangGraph）**

- **[mcp-cn-commerce-agent](https://github.com/liuxzhong-dev/mcp-cn-commerce-agent)** — 基于 MCP 协议的电商数据 Agent。stdio 双向通信，用 Tool Calling 驱动店铺商品与订单查询；mock 代理层免真实企业凭证即可跑通全链路。`MCP · Python · DeepSeek`
- **[price-monitor-agent](https://github.com/liuxzhong-dev/price-monitor-agent)** — 商品价格监控 Agent。Playwright 抓 JS 动态价格，SQLite 存历史，涨跌越过阈值走钉钉告警并导出 CSV。`LangGraph · Playwright · SQLite`
- **[scraping-agent-ai](https://github.com/liuxzhong-dev/scraping-agent-ai)** — 网页抓取 Agent。五节点工作流跑抓取到结构化 JSON，Firecrawl 与 Crawl4AI 双引擎可切，批量任务单条失败不中断。`LangGraph · Firecrawl · DeepSeek`

**LLM 应用与工程**

- **[VideoSummarizer](https://github.com/liuxzhong-dev/video-summarizer)** — 视频链接一键输出结构化中文总结。6 个平台、2 种语音识别、2 家大模型，任一环失败自动降级到本地摘要。`Python · LLM · RAG · PyInstaller`
- **[爪Pro](https://github.com/liuxzhong-dev/paw-pro)** — Windows 桌面自动化。界面之外全部用 ctypes 直调 Win32，自研无边框窗口拖动与提权窗口输入注入。`Python · ctypes · WebView2`
- **[计件本](https://github.com/liuxzhong-dev/jijian-ledger)** — 制衣厂计件工的手机账本，填 6 个字段自动算全天收入，纯离线不联网。`Flutter · SQLite`

**联系**：1191381915@qq.com
