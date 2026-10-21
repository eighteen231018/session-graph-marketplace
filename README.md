# session-graph-marketplace

一个自托管的 Claude Code marketplace，用来分发 [session-graph](https://github.com/eighteen231018/session-graph) 插件。

## 安装

### Claude Code Desktop

在 Code 会话中打开 `+` → **Plugins / Add plugins**，添加 marketplace：

```text
eighteen231018/session-graph-marketplace
```

然后选择 `session-graph` 安装。安装后可在 **Manage plugins** 中启用、禁用或卸载。

### CLI

```bash
claude plugin marketplace add eighteen231018/session-graph-marketplace
claude plugin install session-graph@session-graph-marketplace
```

## 清单

[`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json) 将 `session-graph` 指向插件仓库 `eighteen231018/session-graph`。插件版本以该仓库中的 `.claude-plugin/plugin.json` 为准。
