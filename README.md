# ZeroShell 使用文档

ZeroShell（https://zeroshell.top）是一个 AI API 中转站。

## 三个特点

- **满血**：全原版模型，不降智、不偷换、不缩水。市面上常见的偷工减料（降级模型冒充原版）在这里没有。
- **稳定**：线路稳定，不频繁掉线；多上游动态调度，一个上游出问题自动切到另一个。
- **便宜，且价格全公开**：所有模型价格都在价格页上公开可查，没有隐藏收费。

## 快速开始

1. 注册：用户名 + 密码 + 邮箱验证，约 1 分钟。注册送 ¥0.2 额度，可以先测。
2. 充值：支付宝，¥1 起充，¥1 = $1 额度。首次充值额外赠送 15%（每人一次，单笔赠送上限 ¥50）。
3. 创建令牌：在控制台新建令牌，选一个分组。
4. 接入：按下面的地址和格式调用。

## 接入地址

- OpenAI 兼容接口：`https://zeroshell.top/v1`
- Anthropic 接口（Claude）：`https://zeroshell.top`

## 分组

- 文本：`低价` / `稳定` / `官方` 三个分组，模型相同、线路与价格不同，按需选择。
- 图片 / 视频：图片与视频生成走 `图片` / `视频` 分组，也可以直接用工作台：https://studio.zeroshell.top

## 支持的模型

Claude、GPT、Gemini、DeepSeek、Grok、GLM、Kimi 等，以站内价格页为准：https://zeroshell.top/pricing

## 教程

- [Claude Code 接入](docs/claude-code.md)
- [Codex 接入](docs/codex.md)
- [三招测出中转站有没有偷工减料](https://www.bilibili.com/read/cv53804274)：同题对照、价格是否全公开、¥1 小额试用两天。建议不管用哪家，都先按这三招测一测。

## 联系

- 官网：https://zeroshell.top
- 邮箱：support@zeroshell.top
