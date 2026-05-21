# surge-rules

个人自用 Surge 规则补充仓库，用于存放一些手动维护的外部规则集，方便在 macOS / iOS / iPadOS 的 Surge 配置中同步使用。

## 文件说明

| 文件 | 用途 |
|---|---|
| `surge_manual_direct.list` | 手动直连补充规则 |
| `surge_manual_proxy.list` | 手动代理补充规则 |
| `ForeignDNS.list` | 国外 DNS / DoH / DoT 相关规则 |
| `apple-relay-cloudflare.list` | Apple Relay / Cloudflare 相关补充 |
| `stun.list` | STUN / TURN 端口参考规则 |

## Surge 引用方式

### 手动代理补漏

```ini
RULE-SET,https://raw.githubusercontent.com/yangbiaogao/surge-rules/main/surge_manual_proxy.list,"🇺🇸 US-Snell",extended-matching
