# Rules

适用于 Mihomo/Clash 与 Surge 的分类规则集合。

## 内容

- `clash/`：Rule Provider YAML，以及 `private.mrs`、`cn-ip.mrs`。
- `surge/`：Surge 规则列表。
- `manifest.json`：当前规则版本及文件校验信息。

涵盖 AI、广告、应用净化、国内、Telegram、Google、GitHub、媒体、Apple、
Microsoft 与 Steam 等分类。`cn-ip.mrs` 用于 Mihomo/Clash 的本地 CIDR 匹配；
Surge 的国内 IP 分流使用客户端原生 `GEOIP,CN`。
