# cxxzsh/rules

公开、只读的订阅规则产物仓库。内容由私有的 `cxxzsh/rules-private`
在其来源快照发生实际变化后生成；请不要直接提交或编辑此仓库的规则文件。

## 版本与使用方式

- `manifest.json` 中的 `artifactsCommit` 是当前完整规则版本的不可变提交。
- VPS 订阅生成器读取此清单，再将每个规则 URL 固定到该提交；因此
  `/bak/c` 与 `/bak/s` 会继续引用其生成时的上一版规则。
- 订阅客户端应使用 VPS 的完整 `/c` 或 `/s` 链接，而不是直接订阅本仓库的
  单个规则文件。

## 目录

- `clash/`：Mihomo/Clash rule-provider YAML 和 `private.mrs`、`cn-ip.mrs`。
- `surge/`：Surge 规则列表。

规则按 AI、广告、国内、Telegram、Google、GitHub、媒体、Apple、Microsoft、
Steam 等业务分类发布。`cn-ip.mrs` 仅供 Mihomo/Clash 本地 CIDR 匹配使用；
Surge 国内 IP 分流保持为客户端原生 `GEOIP,CN`。
