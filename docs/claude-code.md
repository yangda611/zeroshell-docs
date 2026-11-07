# Claude Code 接入 ZeroShell

Claude Code 可以通过 Anthropic 兼容接口接 ZeroShell。

## 步骤

1. 在 ZeroShell 控制台（https://zeroshell.top）新建一个令牌，分组选 `官方`。
2. 设置环境变量：

```bash
export ANTHROPIC_BASE_URL="https://zeroshell.top"
export ANTHROPIC_AUTH_TOKEN="你的令牌"
export ANTHROPIC_MODEL="claude-opus-5-5"
```

3. 启动 Claude Code，正常使用。

## 说明

- 令牌按量计费，价格以站内价格页为准；官方分组价格较高，需要便宜的线路可以在控制台换 `稳定` / `低价` 分组。
- 如果遇到模型返回异常，先在控制台确认令牌余额和分组；有问题联系 support@zeroshell.top。
