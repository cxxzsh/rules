# rules

Public, generated subscription rule sets for Clash/Mihomo and Surge. Files are updated only by the private builder repository. Do not edit generated files manually.

## Clash / Mihomo providers

- `https://raw.githubusercontent.com/cxxzsh/rules/main/clash/direct.yaml`
- `https://raw.githubusercontent.com/cxxzsh/rules/main/clash/proxy.yaml`
- `https://raw.githubusercontent.com/cxxzsh/rules/main/clash/reject.yaml`

Use the files as `rule-providers`; map `direct` to `DIRECT`, `proxy` to your proxy policy group, and `reject` to `REJECT` in your own rules.

## Surge rule sets

- `https://raw.githubusercontent.com/cxxzsh/rules/main/surge/direct.list`
- `https://raw.githubusercontent.com/cxxzsh/rules/main/surge/proxy.list`
- `https://raw.githubusercontent.com/cxxzsh/rules/main/surge/reject.list`

Use them with `RULE-SET,<url>,DIRECT`, `RULE-SET,<url>,<your-proxy-policy>`, and `RULE-SET,<url>,REJECT` respectively.
