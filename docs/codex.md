# Codex 接入 ZeroShell

Codex 可以通过 OpenAI 兼容接口接 ZeroShell。

## 步骤

1. 在 ZeroShell 控制台（https://zeroshell.top）新建一个令牌，分组选 `低价` 或 `稳定`。
2. 在 Codex 配置文件 `~/.codex/config.toml` 里写：

```toml
model = "gpt-6.1-sol"
model_provider = "zeroshell"

[model_providers.zeroshell]
name = "ZeroShell"
base_url = "https://zeroshell.top/v1"
env_key = "ZEROSHELL_API_KEY"
```

3. 设置环境变量后启动 Codex：

```bash
export ZEROSHELL_API_KEY="你的令牌"
codex
```

## 说明

- `gpt-6.1-sol` 等模型支持多轮连续对话（Responses API 的 previous_response_id 链式调用）。
- 令牌按量计费，价格以站内价格页为准；有问题联系 support@zeroshell.top。
