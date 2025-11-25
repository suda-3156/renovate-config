# renovate-config

## Usage

- `.github/renovate.json`

```json5
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>suda-3156/renovate-config",
    "github>suda-3156/renovate-config:anytime", // To run renovate at any time
    "github>suda-3156/renovate-config:ignore-test" // To enable automerging without tests
  ]
}
```

## References

- [Shareable Config Presets](https://docs.renovatebot.com/config-presets/#github)
- [hatena/renovate-config](https://github.com/hatena/renovate-config)
- [SpotOnInc/renovate-config](https://github.com/SpotOnInc/renovate-config)
- [koki-develop/renovate-config](https://github.com/koki-develop/renovate-config)
- [Renovate の shareable config preset を作ってリポジトリに導入するメモ](https://zenn.dev/nafuka11/scraps/37851a3522c692)
