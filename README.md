# HermesBee 🐝

> Web Scraping Tools for Developers & AI Agents

[![Gumroad](https://img.shields.io/badge/Store-HermesBee-6366f1)](https://5044216526512.gumroad.com)

HermesBee 提供开发者友好的本地爬虫工具和 AI Agent MCP 套件。无订阅、无月费、数据不出本机。

---

## 产品一览

### 🖥️ 本地爬虫 API

| 产品 | 价格 | 说明 |
|------|------|------|
| [**ScrapeBox**](https://5044216526512.gumroad.com/l/mhxei) | **$29** | 本地运行的 REST 爬虫 API。双击启动，curl 调用。提取 HTML/文本/链接/表格。绕过低中等级反爬。 |
| [**ScrapeBox Pro**](https://5044216526512.gumroad.com/l/xfedun) | **$39** | ScrapeBox + 自动绕过所有等级反爬保护（Cloudflare 等）。一键启动，零配置。 |

### 🤖 MCP Servers（AI Agent 工具）

[什么是 MCP？](https://modelcontextprotocol.io) — 让 Claude Desktop、Cursor、Cline、Windsurf 拥有浏览器和爬虫能力。

| 产品 | 价格 | 能力 |
|------|------|------|
| [**CF Bypass Browser**](https://5044216526512.gumroad.com/l/vueszs) | $25 | 绕过所有 Cloudflare + 点击/输入/截图/滚动/翻页 |
| [**Unified Scraper**](https://5044216526512.gumroad.com/l/jusjsp) | $19 | 智能爬虫，传 URL 返回内容，自动绕 Cloudflare |
| [**Stealth Browser**](https://5044216526512.gumroad.com/l/lxuqkk) | $15 | 隐身浏览器，绕中低反爬，截图+Cookie |
| [**Smart Scraper**](https://5044216526512.gumroad.com/l/xjggdb) | $15 | 基础爬虫，提取标题/正文/链接/图片 |
| [**Domain Monitor**](https://5044216526512.gumroad.com/l/rxmzx) | $10 | 域名 whois 过期监控 |
| [**Income Monitor**](https://5044216526512.gumroad.com/l/atwirg) | $10 | 挂机平台收益汇总监控 |

---

## 快速开始

### ScrapeBox

```bash
# 1. 下载 → 解压
# 2. 安装依赖 (Windows: setup.bat / Mac: bash setup.sh)
# 3. 启动 (双击 start.bat / bash start.sh)
# 4. 使用
curl "http://localhost:8080/text?url=https://example.com"
```

### MCP Servers

配置到你的 Claude Desktop / Cline / Cursor：

```json
{
  "mcpServers": {
    "cf-bypass-browser": {
      "command": "python3",
      "args": ["path/to/cf_bypass_browser.py"]
    }
  }
}
```

---

## 技术栈

- **Patchright** — 隐身浏览器引擎
- **FlareSolverr** — Cloudflare 绕过
- **Playwright** — 浏览器自动化
- **Python** — 全产品

---

## 购买

全部产品在 Gumroad 销售，**一次性买断**，无月费，永久使用。

➡️ [**HermesBee Store**](https://5044216526512.gumroad.com)

---

## 许可证

各产品遵循自带的 License 协议。
